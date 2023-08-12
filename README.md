# white_search

## 説明

manual_input.txt の空行と ">" から始まる行を削除して manual_input_ready.txt を得、それを Google カスタムサーチの GUI にコピペしています。

得られた Google カスタムサーチは次の URL で公開しています：
https://cse.google.com/cse?cx=35fc1913a6666419b

GUI へのコピペと更新は手動ですが、このリポジトリは私の手元のサイトリストをほぼリアルタイムで反映しているため、こちらの中身は一般に上記 URL で実際に使われているサイトリストに先行しています。

## そのうちやりたいこと

* 国連機関のドメインが並んでるところとか普通にアホなので、ああいうやつは別のファイルで保持して勝手に挿入されるようにしたい
* Google カスタムサーチの GUI からは逃れられないっぽいが、アノテーションファイルのアップロードを使用したほうが更新時のロード時間が短い可能性があり、アノテーションファイルを自動生成したい