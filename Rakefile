require 'rake/testtask'


#testディレクトリ以下（サブディレクトリを含む）にある、
#_test.rbという名前で終わるファイルを実行対象にする。
Rake::TestTask.new do |t|
    t.pattern = 'test/**/*_test.rb'
end

#デフォルトのタスクに設定することで、
#rakeコマンドでタスク名を指定しない場合に適用される
task default: :test
