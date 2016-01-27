# 開発プロジェクト(Maven Project)の構成

* シングル? マルチ?
  - xxx-api only ?
  - xxx-api + xxx-domain
  - TERASOLUNAはマルチ構成推奨(レイヤ間の依存性の逆転を防ぐ目的)だが・・・
  - xxx-envは不要そう(.yml + @Profile)


# REST API開発関連(@RestController)
TERASOLUNAガイドラインのTODO部分

* リソースの条件付き更新の制御
    ※ TERASOLUNAガイドラインはベストエフォート
* リソースの条件付き取得の制御
    ※ TERASOLUNAガイドラインはベストエフォート
* リソースのキャッシュ制御
    ※ TERASOLUNAガイドラインはベストエフォート
* バージョニング
    ※ TERASOLUNAガイドラインはベストエフォート


# REST API開発関連(Security)
TERASOLUNAガイドラインのTODO部分

* 認証・認可
    ※ OAuth2(Spring Security OAuth 2)はTERASOLUNAで執筆する?


# REST API開発関連(Spring Boot)
現時点のTERASOLUNAのガイドでカバーできない部分

* Servlet Containerに通知されたエラーのハンドリング方法
  - http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#boot-features-error-handling

* File Uploadのコンフィギュレーション
  - http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#howto-multipart-file-upload-configuration

* ObjectMapperのカスタマイズ方法
  - http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#howto-customize-the-jackson-objectmapper


# APサーバ関連

* 組み込みサーブレットコンテナのコンフィギュレーション方法
  - http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#boot-features-embedded-container

* Tomcatのコンフィギュレーション＋カスタマイズ方法
  - http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#howto-configure-tomcat


# ノウハウ関連

* Developer tools
  - http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#using-boot-devtools

* STS?
  - なにかれば・・

* Lombok
  - TERASOLUNAのAppendixでも触れてはいる。

* REST API仕様書の自動生成
  - swagger
  - Spring REST Doc ?



