# 🌐 Project Overview

このリポジトリは、多層的・交錯的に展開される複数のプロジェクトを統合的にナビゲートするハブです。

## 🎯 ビジョンと目的

私たちは、技術・芸術・自然・社会の交差点に立ち、未来の創造的環境を共に築くことを目指します。  
ここに集まるプロジェクト群は、それぞれが独立して開発されながらも、相互に接続・影響し合い、豊かなエコシステムを形成しています。

## 🧭 プロジェクト一覧と概要

| プロジェクト名 | 説明 | リンク |
|----------------|------|--------|
| **アニメーションソフト改善** | 群制御や教育向けアニメーション制作支援ツールの改善 | [animation-improver](https://github.com/your-org/animation-improver) |
| **森林型アーカイブ構築** | 自然・記憶・文化を有機的に保存・探索するメディアアーカイブ | [forest-archive](https://github.com/your-org/forest-archive) |
| **群制御システム** | ドローンやロボットのBoid的群制御アルゴリズムとその応用 | [swarm-control-system](https://github.com/your-org/swarm-control-system) |
| **人と群ロボットのインタラクション** | 群ロボットと人間の関係を設計するインタラクティブ技術群 | [human-swarm-interface](https://github.com/your-org/human-swarm-interface) |
| **マルチユースドローン開発** | 教育・農業・アートなど多目的なドローン設計と組立ガイド | [multiuse-drone](https://github.com/your-org/multiuse-drone) |
| **インクルーシブUI開発** | 多様な人が関われるUI/UX設計と共創インターフェース | [inclusive-ui](https://github.com/your-org/inclusive-ui) |

## 🕸️ 関係性マップ（全体構造図）

以下の構造図は、各プロジェクト間の接続・連携を示しています：

```mermaid
graph TD
    overview([Project Overview Hub])

    subgraph Animation Tools
        anim[Animation Improver]
    end

    subgraph Swarm Robotics
        swarm[Swarm Control System]
        humanSwarm[Human-Swarm Interface]
        drone[Multiuse Drone Development]
    end

    subgraph Media & Archive
        archive[Forest Archive]
    end

    subgraph Human Experience
        ui[Inclusive UI Development]
    end

    overview --> anim
    overview --> swarm
    overview --> archive
    overview --> ui

    swarm --> humanSwarm
    swarm --> drone
    humanSwarm --> ui
    archive --> ui
    archive --> anim
