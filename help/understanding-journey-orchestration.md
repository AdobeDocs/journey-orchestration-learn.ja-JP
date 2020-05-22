---
title: Understanding Jureny Orchestration
description: 遍歴オーケストレーションの概念、それが有効にする使用例のタイプ、およびJurney Orchestrationの機能の主な要素を理解します。
feature: Journey Orchestration
topics: Introduction
kt: 2773
audience: user, developer
doc-type: video
activity: understand
translation-type: tm+mt
source-git-commit: 795b30fe984b7fe715789144e8c421028d7d32ac
workflow-type: tm+mt
source-wordcount: '342'
ht-degree: 0%

---


# Understanding [!UICONTROL Jureny Orchestration]

## Introduction to [!UICONTROL Jureny Orchestration]

[!UICONTROL Jureny Orchestration] では、イベントやデータソースに保存されたコンテキストデータを活用した、リアルタイムのオーケストレーションの使用例を構築できます。

[!UICONTROL Jureny Orchestration] は、Adobe Experience Platformと統合されたアプリケーションサービスです。 インテリジェントでオープンなエコシステムを提供し、マーケティングから業務、サービスまで、ビジネスに必要なあらゆるチャネルに対して、拡張性の高いイベントベースのエンゲージメントを通じて、関連するすべてのライブデータをアクティブ化します。 [!UICONTROL Jureny Orchestration] は、Adobe Experience Platformや外部配信システムから得た任意のデータを利用して、説得力のあるエクスペリエンスを作成し、配信できます。

以下のビデオでは、

* [!UICONTROL 旅の調整の概念]
* 有効にする使用例のタイプ
* [!UICONTROL Jureny Orchestrationの機能の主な要素]

>[!VIDEO](https://video.tv.adobe.com/v/29307?quality=12)

## 遍歴の設定方法

旅の準備の主な手順は次のとおりです。

1. [ストリーミングイベントの構成](/help/configuring-journey-orchestration/configure-streaming-events.md) — この設定は必須です。 [!UICONTROL Jureny Orchestration] はイベントをリッスンするように設計されています。
2. [データソースの設定](/help/configuring-journey-orchestration/configure-data-sources.md) — この設定は、ジャーニーがイベントペイロードからのローカルデータのみを利用する場合は不要です。
3. [カスタムアクションの設定](/help/configuring-journey-orchestration/configure-actions.md): JSON形式のペイロードを使用して呼び出すことのできるサードパーティプロバイダーのサービスを使用する場合 [!DNL REST API] は必須です

>[!NOTE]
>これらの設定手順では、技術的な知識が必要です。 Experience Data Model(XDM) [(](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/understanding-the-xdm-system-and-experience-data-model.html)Experience Data Model)の詳細およびXDM Experienceイベントスキーマ [の作成方法を理解している必要があります](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/create-your-first-schema-with-out-of-the-box-components.html)。

## 遍歴の作成、投稿、分析方法

1. [遍歴の作成](/help/create-a-journey.md)
2. [遍歴の検証と公開](/help/validate-and-publish-a-journey.md)
3. [レポートツールを使用した遍歴の分析](/help/analyze-a-journey-via-reporting-tools.md)

## その他のリソース

* [ジャーニーオーケストレーションヘルプセンター](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html)
* [Adobe Experience Platformチュートリアル](https://docs.adobe.com/content/help/en/platform-learn/tutorials/overview.html)
* [Jureny Orchestrationのヘルプの検索方法](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform Mobile SDK — 起動](https://docs.adobe.com/content/help/en/core-services-learn/tutorials/launch-mobile/understanding-the-mobile-sdks.html)
* [Adobe Experience Platform Location Service](https://docs.adobe.com/content/help/en/places/using/home.html)
