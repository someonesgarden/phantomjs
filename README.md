
phantom.js


#　サイズ指定しない場合
`
docker run --rm -it -v $(pwd)/data:/data --name pmmm pmtm /srv/var/phantomjs/examples/rasterize.js http://someonesgarden.org /data/someonesgarden.png  1200 600
`

# サイズ指定する場合
`
docker run --rm -it -v $(pwd)/data:/data --name pmmm pmtm /usr/bin/myRasterize.js http://someonesgarden.org /data/someonesgarden3.png 100 30
`

参考
<http://qiita.com/edvakf@github/items/7db522d4626ad46a8004>
<http://aj.ayuta.co.jp/post/30577164224/phantomjs%E3%83%96%E3%83%A9%E3%82%A6%E3%82%B6%E3%82%92%E4%BD%BF%E3%82%8F%E3%81%9A%E3%81%ABweb%E3%83%9A%E3%83%BC%E3%82%B8%E3%81%AE%E7%94%BB%E9%9D%A2%E3%82%AD%E3%83%A3%E3%83%97%E3%83%81%E3%83%A3%E3%82%92%E5%8F%96%E3%82%8B%E6%96%B9%E6%B3%95>
