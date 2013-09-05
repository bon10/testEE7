testEE7
=======

this is test project. Using Java EE 7,Maven, WildFly 8(GlassFish 4), JAX-RS,hibernate and JSON.  
これはテストプロジェクトです。
JavaEE7とかで色々おっためすやつです。


#使い方
`testEE7`というディレクトリを作ってそこに`git clone`してくだしあ。

#デプロイ方法
Eclipse場合は、プロジェクト右クリック > エクスポート > war を選択する感じ。  
NetBeansやコンソールは分かりません。  

デプロイ後はお好きなJava7対応APサーバにデプロイしてください。  

#注意事項
Eclipseで手動デプロイではなく、プロジェクトを「サーバで実行」とした場合、  
JAX-RSが上手く動きません。(URLが404 Not Foundになる)  
なので、手動で色々やるのが面倒な方はNet Beans + GlassFish 4 の環境が無難です。
