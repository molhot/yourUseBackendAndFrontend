# yourUseBackendAndFrontend
使うバックエンドとフロントエンドを決める

# Backendの種類

## Nodejs 
Express.js	軽量・柔軟な定番フレームワーク  
NestJS	Angularライクな構造、TypeScriptベース  
Koa.js	Expressの後継、ミニマル  
Fastify	高速・低オーバーヘッド  
Hapi.js	エンタープライズ向け、設定重視  
Sails.js	MVC構造、Railsライク  
LoopBack	API自動生成、Microservices向け  
AdonisJS	Laravelライクな構造、フルスタック  

## python 
Django	フルスタック、高機能、ORM内蔵  
Flask	軽量・ミニマル、拡張しやすい  
FastAPI	非同期対応、Swagger自動生成、モダン  
Tornado	非同期対応、高スケーラビリティ  
Bottle	単一ファイルで完結、超軽量  
Pyramid	柔軟な設計、スケーラブル  
Falcon	API専用、高速  

## Ruby 
Ruby on Rails	MVC、Convention重視、爆速開発  
Sinatra	シンプル、軽量  
Hanami	モジュール分割、スケーラブル  
Padrino	Sinatra拡張、高機能化  

## PHP 
Laravel	モダン、ORM (Eloquent)、人気高  
Symfony	コンポーネント指向、柔軟  
CodeIgniter	軽量・高速  
Yii	パフォーマンス重視  
Zend Framework / Laminas	エンタープライズ向け  
Phalcon	Cで書かれた高速PHPフレームワーク  
CakePHP	Railsライク、シンプル設計  

## Java 
Spring Boot	モダンJavaの定番、依存注入、マイクロサービス対応  
Jakarta EE (旧Java EE)	エンタープライズ向け  
Micronaut	軽量、高速起動、サーバレス対応  
Quarkus	GraalVM対応、クラウドネイティブ  
Dropwizard	シンプル、Fat JAR構成  
Play Framework	Scala/Java両対応、非同期対応  

## Go 
Gin	高速・軽量、人気高  
Echo	Ginに似たシンプル設計  
Fiber	Express風、超高速  
Revel	フルスタック、MVC構造  
Beego	フル機能、ORM内蔵  
Chi	ネストルーティング対応、ミニマル  

## C#
ASP.NET Core クロスプラットフォーム、高性能  
Akka HTTP	アクターモデル、並列処理向け  

## Scala 
Play Framework	Javaとの共通基盤、非同期対応  
Akka HTTP	アクターモデル、並列処理向  

## Kotlin 
Ktor	Kotlin製、DSL風にルーティング記述可能  
Spring Boot (Kotlin対応)	Kotlinとも互換あり  
http4k	関数型志向、軽量フレームワーク  

## Rust
Actix Web	非常に高速、非同期、Actorベース  
Rocket	シンプルでエルゴノミクス重視  
Warp	tokioベース、超高速  
Axum	Towerエコシステム準拠、型安全重視  

## Elixir
Phoenix	高並行性、WebSocket対応（LiveView）  
Plug	Rackライクなミドルウェア抽象化  

## C/C++
Crow (C++)	C++版Express風  
CppCMS	高性能、スレッドセーフ  
Pistache (C++)	モダンC++でREST API構築  

## D言語 
Vibe.d イベント駆動、非同期IO  

## Perl
Dancer2	Sinatraライク  
Mojolicious	非同期、リアルタイム対応  

## Haskell
Yesod	型安全、コンパイル時バリデーション  
Scotty	Sinatraライク、軽量  
Servant	API設計と型が密結合  

## Swift 
Vapor SwiftでWeb API開発、非同期対応  

# FrontEnd種類
## JS 
React UIライブラリ、コンポーネント指向、人気No.1  
Next.js Reactのフルスタックフレームワーク（SSR/SSG）  
Vue.js 軽量・習得しやすい、MVVMアーキテクチャ  
Angular フルスタックSPA、TypeScriptベース、大規模向け  
Qwik 遅延ロード（resumability）重視、超高速  
Alpine.js HTML中で動作、Tailwindとの相性◎  

## CSS 
Tailwind CSS	ユーティリティファースト、モダンCSS設計  
Bootstrap	伝統的UIフレームワーク、コンポーネント豊富  
Chakra UI コンポーネント駆動のUI（React用）  
Element Plus Vue 3対応のUIフレームワーク  

## モバイル対応
React Native	iOS/Android	Reactベース  
Expo	React Native拡張	設定不要で簡単導入  
Flutter	iOS/Android/Web/Desktop	Dart使用、UI高速  
Ionic	iOS/Android/Web	Angular/React/Vue対応  
Capacitor	モバイル/デスクトップ	Ionic製、Web技術活用  
Electron	デスクトップアプリ	JS/HTML/CSSでアプリ開発  
Tauri	デスクトップアプリ	Rust + WebView、軽量  

--以下は調べる  
## 静的サイトジェネレーター（SSG）
Gatsby	React	高速なSSG、GraphQL連携  
Next.js	React	SSR/SSG両対応  
Nuxt.js	Vue	VueのSSG/SSR対応  
Hugo Goベース 爆速SSG、Markdown中心  
