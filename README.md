# Go
<html>
<head>
</head>
<pre>
go言語インストール
いれるバージョンは1.4
<a href="../Other/go/go1.4.linux-386.tar.gz">ソース</a>をダウンロードする。


# cd /usr/local/  <==ここで解凍する
# tar xvfz /..../go1.4.linux-386.tar.gz


解凍し終わったら、
/etc/profileに追記


export PATH=$PATH:/usr/local/go/bin
と追記する


そして、再起動するか、
sourceコマンドで適応する。




「hello, world」と出力するプログラム
--------------------------------------
package main

import "fmt"

func main() {
	fmt.Printf("hello, world\n")
}
-------------------------------------


</pre>
</html>
