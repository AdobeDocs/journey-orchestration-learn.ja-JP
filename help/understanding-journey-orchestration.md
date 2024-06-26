---
title: Journey Orchestration について
description: Journey Orchestration の概念、Journey Orchestration によって実現できるユースケースのタイプおよび Journey Orchestration の主な要素の仕組みを理解します。
feature: Overview
topics: Introduction
jira: KT-2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
role: User, Admin
exl-id: db4f69bb-183c-4376-9791-eb6b1f78ab32
source-git-commit: 9db2765ee5e9520280711a6b1fe3c618963f6f87
workflow-type: ht
source-wordcount: '296'
ht-degree: 100%

---

# [!UICONTROL Journey Orchestration について]

[!UICONTROL Journey Orchestration] を利用すると、イベントやデータソースに格納されているコンテキストデータを使用して、リアルタイムオーケストレーションのユースケースを実現することができます。

## [!UICONTROL Journey Orchestration の概要]

[!UICONTROL Journey Orchestration] は、Adobe Experience Platform と統合されたアプリケーションサービスです。インテリジェントでオープンなエコシステムを提供し、マーケティングから業務さらにサービスに至るまで、ビジネスに必要なあらゆるチャネルにわたって、拡張性の高いイベントベースのエンゲージメントを通じて、関連するすべてのライブデータを有効化します。[!UICONTROL Journey Orchestration] では、Adobe Experience Platform や外部配信システムの任意のデータを使用して、魅力的なエクスペリエンスを作成および配信できます。

以下のビデオの内容は次のとおりです。

* [!UICONTROL Journey Orchestration] の概念
* Journey Orchestration で有効になるユースケースのタイプ
* [!UICONTROL Journey Orchestration] の動作の主な要素

>[!VIDEO](https://video.tv.adobe.com/v/29307?learn=on){transcript=true}

## ジャーニーの設定方法

ジャーニー構築の準備の主な手順は次のとおりです。

1. [ストリーミングイベントの設定](/help/configuring-journey-orchestration/configure-streaming-events.md) - [!UICONTROL Journey Orchestration] はイベントをリッスンするように設計されているので、この設定は必須です。
1. [データソースの設定](/help/configuring-journey-orchestration/configure-data-sources.md) - ジャーニーでイベントペイロードからのローカルデータのみを使用する場合、この設定は必要ありません。
1. [カスタムアクションの設定](/help/configuring-journey-orchestration/configure-actions.md)：JSON 形式のペイロードを使用して [!DNL REST API] で呼び出すことができる、サードパーティプロバイダーのサービスを使用する場合は必須です。

>[!NOTE]
>
>これらの設定手順を実行するには、専門知識が必要です。[エクスペリエンスデータモデル（XDM）](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schemas-and-experience-data-model.html?lang=ja)についてと [XDM エクスペリエンスイベントスキーマの作成方法](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=ja)を熟知している必要があります。

## ジャーニーの作成、公開、分析方法

1. [ジャーニーの作成](/help/building-a-journey/creating-a-journey.md)
1. [ジャーニーの検証と公開](/help/validate-and-publish-a-journey.md)
1. [レポートツールを使用したジャーニーの分析](/help/analyze-a-journey-via-reporting-tools.md)

## その他のリソース

* [Journey Orchestration ヘルプセンター](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ja)
* [Adobe Experience Platform チュートリアル](https://experienceleague.adobe.com/docs/platform-learn/tutorials/overview.html?lang=ja)
* [Journey Orchestration に関するヘルプの参照方法](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform モバイル SDK - Launch](https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/overview.html?lang=ja)
* [Adobe Experience Platform Location Service](https://experienceleague.adobe.com/docs/places/using/home.html?lang=ja)
