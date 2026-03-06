# 国立国会図書館サーチ 外部提供インタフェース仕様書 Web版

国立国会図書館サーチの外部提供インタフェース仕様書（PDF）を、閲覧しやすい Web ページとして再構成したものです。

## 概要

- **原典**: 国立国会図書館サーチ 外部提供インタフェース仕様書 第 1.3 版（2025.3.26）
- **生成**: Claude Sonnet 4.6（`claude-sonnet-4-6` / Anthropic）により PDF から自動生成
- **内容**: 仕様書本体 + 附録1〜3 の全内容を収録

> このページの内容は AI によって自動生成されたものです。正確性の保証はありません。必ず原典 PDF を参照してください。

## ファイル構成

```
ndl-doc/
├── index.html                                          # Web ドキュメント本体
├── ndlsearch_api_20250326.pdf                          # 仕様書本体（第 1.3 版）
├── 附録1_データプロバイダ一覧と外部提供インタフェース対応表.pdf   # 附録1（2025.11.5）
├── 附録2_データグループID・mediaType一覧.pdf              # 附録2（2024.4.1）
└── 附録3_コレクションコード・Access Rights一覧 .pdf       # 附録3（2025.9.16）
```

## 収録内容

### 仕様書本体
| # | インタフェース | 入力 | 出力 |
|---|---|---|---|
| 1 | SRU | URL（CQL クエリ） | XML |
| 2 | OpenSearch | URL | RSS 2.0 |
| 3 | OpenURL | URL | HTML |
| 4 | OAI-PMH | URL | XML |
| 5 | 書影 API | URL | JPEG |

### 附録
- **附録1**: データプロバイダ一覧（現行 111 件・連携停止済 28 件・書影 API 対象）
- **附録2**: データグループ ID・mediaType 一覧（資料形態・資料種別・コレクション）
- **附録3**: コレクションコード一覧（A 系: デジタル化資料 / B 系: 電子書籍・電子雑誌）・Access Rights 一覧

## 参考リンク

- [国立国会図書館サーチ](https://ndlsearch.ndl.go.jp)
- [DC-NDL（RDF）フォーマット仕様](https://ndlsearch.ndl.go.jp/renkei/dcndl)
- [SRU 基本仕様](http://www.loc.gov/standards/sru/)
- [OAI-PMH 基本仕様](http://www.openarchives.org/OAI/openarchivesprotocol.html)
- [OpenSearch 基本仕様](https://github.com/dewitt/opensearch)
