
# ライフサイエンス分野の統合データベースの活用事例の演習
<p><span style="font-size:25px;display:inline-block;line-height:130%;text-indent:0px">遺伝子発現データベースの活用法</span>　　　　担当：小野浩雅</p>
<p>目次</p>
<div class="contents">
<a id="contents_1"></a>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li><a href="#e531771f"> 自己紹介 </a></li>
<li><a href="#xff65fc3"> 統合TV </a></li>
<li><a href="#taf036b7"> 遺伝子発現データベースに関する統合TV </a></li>
<li><a href="#t5ad14b0"> BioGPS </a>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li><a href="#k6b911bc"> 【実習1】BioGPSを使ってある遺伝子の発現プロファイルを調べる </a></li></ul></li>
<li><a href="#e22736da"> 【参考1】RefEX </a></li>
<li><a href="#r6287e42"> NCBI Gene Expression Omnibus (GEO) </a>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li><a href="#mcb0ec77"> 【実習2】GEOに登録されているマイクロアレイデータを検索して、さらにデータセットブラウザ(Dataset browser)を利用して解析する </a></li>
<li><a href="#a83d5bfe"> 【発展編・その1】GEOを使って、自分の興味のある遺伝子の（ある実験条件下における）発現状況を調べる </a></li>
<li><a href="#ze44dc22"> 【発展編・その2】GEOを使って、自分の興味のあるマイクロアレイ実験データセットを検索&amp;生データをダウンロードする </a></li></ul></li>
<li><a href="#rdfd50d4"> 【参考2】遺伝子発現バンク(GEO)目次、通称「GEO目次」 </a></li>
<li><a href="#zef09660"> DAVID: The Database for Annotation, Visualization and Integrated Discovery </a>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li><a href="#z6529d62"> マイクロアレイデータの準備 </a></li>
<li><a href="#y04a402a"> 【実習3】DAVIDを用いて、発現データの結果を生物学的に解釈する </a></li></ul></li></ul>
</div>

<h3 id="content_1_0"><a id="e531771f" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#e531771f" title="e531771f"><span class="sanchor">_</span></a> 自己紹介  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li><a href="http://dbcls.rois.ac.jp/~hono/dokuwiki/" rel="nofollow">小野 浩雅</a> (おの ひろまさ)</li>
<li><a href="http://dbcls.rois.ac.jp/index.html" rel="nofollow">ライフサイエンス統合データベースセンター</a>にて<a href="http://togotv.dbcls.jp" rel="nofollow">統合TV</a>のProducer &amp; Assistant Director &amp; Curator</li></ul>

<div class="jumpmenu"><a href="#navigator">&uarr;</a></div><h3 id="content_1_1"><a id="xff65fc3" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#xff65fc3" title="xff65fc3"><span class="sanchor">_</span></a> <a href="http://togotv.dbcls.jp" rel="nofollow">統合TV</a>  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>統合TVは、生命科学分野の有用なデータベースやウェブツールの活用法を動画で紹介するウェブサイトです。</li>
<li>ユーザーの使いやすさを徹底的に志向した”使い倒し”系！</li>
<li>番組検索や詳細情報は統合TVまとめサイト <a href="http://togotv-curated.dbcls.jp" rel="nofollow">統合TV Curated</a> で！</li>
<li>今日の内容の復習に使えますし、これからの研究室ライフの充実（!?）のために使い倒してください。そして良いと思ったら先輩後輩先生にぜひ宣伝してください！</li></ul>

<div class="jumpmenu"><a href="#navigator">&uarr;</a></div><h3 id="content_1_2"><a id="taf036b7" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#taf036b7" title="taf036b7"><span class="sanchor">_</span></a> <span style="font-size:20px;display:inline-block;line-height:130%;text-indent:0px">遺伝子発現データベース</span>に関する統合TV  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li><a href="http://togotv.dbcls.jp/?category=%C8%AF%B8%BD%BE%F0%CA%F3" rel="nofollow">統合TVの「発現情報」タグをクリック！ </a></li>
<li><a href="http://togotv-curated.dbcls.jp/contents/category/expression#%E9%81%BA%E4%BC%9D%E5%AD%90%E3%83%BB%E3%82%BF%E3%83%B3%E3%83%91%E3%82%AF%E8%B3%AA%E7%99%BA%E7%8F%BE%E3%82%92%E7%B6%B2%E7%BE%85%E7%9A%84%E3%81%AB%E8%AA%BF%E3%81%B9%E3%81%9F%E3%81%84" rel="nofollow">統合TV Curatedの発現制御解析から探す</a></li></ul>

<div class="jumpmenu"><a href="#navigator">&uarr;</a></div><h3 id="content_1_3"><a id="t5ad14b0" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#t5ad14b0" title="t5ad14b0"><span class="sanchor">_</span></a> <a href="https://biogps.gnf.org/" rel="nofollow"><span style="font-size:20px;display:inline-block;line-height:130%;text-indent:0px">BioGPS</span></a>  </h3>
<p><span style="color:green">ヒト、マウス、ラットのさまざまな組織や細胞(株)における遺伝子発現プロファイルのデータベース</span></p>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li><a href="https://biogps.gnf.org/" rel="nofollow">BioGPS</a>はAffymetrix社製のマイクロアレイである<span class="noexists">GeneChip<a href="http://MotDB.DBCLS.jp/?cmd=edit&amp;page=GeneChip&amp;refer=AJACS26%2Fhono">?</a></span>を用いた遺伝子発現プロファイルのデータベース。</li>
<li><a href="http://symatlas.gnf.org/" rel="nofollow">GNF SymAtlas</a><a href="http://togotv.dbcls.jp/20070816.html" rel="nofollow">【参考動画】</a>のメジャーアップデート版。</li>
<li>マウスのエキソンアレイのデータが追加されたので、遺伝子のスプライシングバリアント(Splicing variant)の発現状況も調べることが可能。</li>
<li>検索した遺伝子に対して、種々の外部データベースに横断検索することができる。</li></ul>

<div class="jumpmenu"><a href="#navigator">&uarr;</a></div><h3 id="content_1_4"><a id="k6b911bc" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#k6b911bc" title="k6b911bc">_</a> 【実習1】BioGPSを使ってある遺伝子の発現プロファイルを調べる  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li><a href="http://togotv.dbcls.jp/20110120.html#p01" rel="nofollow">【使い方参考動画】</a>、<a href="http://togotv.dbcls.jp/20100829.html#p01" rel="nofollow">【講習会動画】</a><a href="http://lifesciencedb.jp/image/small_video_icon.png" rel="nofollow"><img src="http://lifesciencedb.jp/image/small_video_icon.png" alt="http://lifesciencedb.jp/image/small_video_icon.png" /></a></li>
<li>1. <a href="https://biogps.gnf.org/" rel="nofollow">https://biogps.gnf.org/</a>を開きます。</li>
<li>2.骨格筋の分化決定遺伝子であるMyogenic differentiation 1(MyoD)の発現プロファイルを調べてみましょう。中央の検索窓に「myod」と入力し、「search」を押します。</li>
<li>3. 表示された検索結果の中から「ID 4654」をクリックします。</li>
<li>4. 最初はヒトのマイクロアレイデータが表示されます。</li>
<li>5. 画面左側の三角形をクリックすることでサイドバーを非表示にできます。非表示にすることで画面を広く使うことができます。</li>
<li>6. ページ内のウインドウは通常のウインドウと同じようにドラッグによる移動やサイズの変更などを行うことができます。 歯車マークのメニューから&quot;Open in Browser&quot; を選択すると、新しいタブで表示できます。</li>
<li>7. &quot;Search&quot; と書かれた窓に単語(組織名など)を入力すると、その単語の含まれた部分が赤くハイライト表示されます。今回は &quot;Muscle&quot; と入力してみます。</li>
<li>8. &quot;Zoom&quot; のバーを用いることで、グラフの表示範囲を調整することが出来ます。</li>
<li>9. 発現量を示すバーをクリックすると発現強度の値が表示されます。</li>
<li>10. &quot;Chart Type&quot; を初期設定の&quot;bar&quot; から&quot;plot&quot;に変更できます。表示がどのように変わるでしょうか？</li>
<li>11. マイクロアレイデータ右上の「Species: Hs」をクリックするとマウスやラットを選択できるので、「M. musculus (Mouse)」をクリックしてマウスのデータを表示できます。</li>
<li>12. MyoDはどの組織、細胞で強く発現しているでしょうか？</li>
<li>13. &quot;Static Image&quot; をクリックすると、ズームや検索機能などのついていない、画像だけのグラフで表示されます。低スペックなマシンでは、こちらの方が軽快に動作するでしょう。</li>
<li>14. 場合によっては右端のプルダウンメニューから複数の項目を選択できる場合があります。これはどのようなケースが考えられるでしょうか。</li>
<li>15. 「Correlation」タブをクリックして検索すると、発現パターンが似ている他の遺伝子を検索できますが、どのような遺伝子が出てくるでしょうか？</li>
<li>16. &quot;Downloads&quot; をクリックすると現在表示しているデータを CSV 形式でダウンロードできます。</li></ul>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>17. 右上の「default rayout」をクリックすると、検索した遺伝子に関するマイクロアレイデータ以外のデータが閲覧できますが、どのようなデータが閲覧できるのか調べてみましょう。</li>
<li>18. 左上の「Search」タグをクリックして検索画面にもどり、自分の興味ある遺伝子について同様に検索してみましょう。
すぐに自分の興味ある遺伝子が浮かばない場合は、話題の<a href="http://ja.wikipedia.org/wiki/%E4%BA%BA%E5%B7%A5%E5%A4%9A%E8%83%BD%E6%80%A7%E5%B9%B9%E7%B4%B0%E8%83%9E" rel="nofollow">iPS細胞</a>を作るために必要な4因子（Oct3/4・Sox2・Klf4・c-Myc）がどの組織で発現しているかを検索してみましょう。</li></ul>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【余談】
BioGPSのiPhoneアプリが無料で公開されていますので、「あの遺伝子はどの組織で発現してるのかな？」とふと思いついたときにお手持ちのiPhoneで遺伝子発現を調べられます。</li></ul>

<div class="jumpmenu"><a href="#navigator">&uarr;</a></div><h3 id="content_1_5"><a id="e22736da" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#e22736da" title="e22736da"><span class="sanchor">_</span></a> 【参考1】<a href="http://togoexp.dbcls.jp/RefEx/" rel="nofollow">RefEX</a>  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li><a href="http://togotv.dbcls.jp/20100618.html#p01" rel="nofollow">使い方参考動画</a><a href="http://lifesciencedb.jp/image/small_video_icon.png" rel="nofollow"><img src="http://lifesciencedb.jp/image/small_video_icon.png" alt="http://lifesciencedb.jp/image/small_video_icon.png" /></a></li>
<li><a href="http://togoexp.dbcls.jp/RefEx/" rel="nofollow">RefEX</a> （Reference Expression dataset）は、ライフサイエンス統合データベースセンター（DBCLS）が提供する4種類の異なる手法 （EST, <span class="noexists">GeneChip<a href="http://MotDB.DBCLS.jp/?cmd=edit&amp;page=GeneChip&amp;refer=AJACS26%2Fhono">?</a></span>, CAGE, RNA-seq）によるヒトおよびマウスの遺伝子発現データのリファレンスデータセットです。複数の手法による客観的な遺伝子発現データの比較が可能となるウェブインターフェースが用意されていることに加えて、個々の遺伝子については染色体領域や遺伝子ファミリー（<span class="noexists">InterPro<a href="http://MotDB.DBCLS.jp/?cmd=edit&amp;page=InterPro&amp;refer=AJACS26%2Fhono">?</a></span>）、Gene Ontology に基づく生物学的機能別に検索ができる他、発現パターンから探すことが可能になっています。</li>
<li>現在もさらに使いやすくなるようアップデート作業中です。</li></ul>
<hr class="full_hr" />

<div class="jumpmenu"><a href="#navigator">&uarr;</a></div><h3 id="content_1_6"><a id="r6287e42" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#r6287e42" title="r6287e42"><span class="sanchor">_</span></a> <a href="http://www.ncbi.nlm.nih.gov/geo/" rel="nofollow"><span style="font-size:20px;display:inline-block;line-height:130%;text-indent:0px">NCBI Gene Expression Omnibus (GEO)</span></a>  </h3>
<p><span style="color:green">世界最大の遺伝子発現（<a href="http://ja.wikipedia.org/wiki/DNA%E3%83%9E%E3%82%A4%E3%82%AF%E3%83%AD%E3%82%A2%E3%83%AC%E3%82%A4" rel="nofollow">マイクロアレイ</a>）データベース（レポジトリ）</span></p>

<div class="jumpmenu"><a href="#navigator">&uarr;</a></div><h3 id="content_1_7"><a id="mcb0ec77" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#mcb0ec77" title="mcb0ec77">_</a> 【実習2】GEOに登録されているマイクロアレイデータを検索して、さらにデータセットブラウザ(Dataset browser)を利用して解析する  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li><a href="http://togotv.dbcls.jp/20090221.html#p01" rel="nofollow">【使い方参考動画1】</a><a href="http://lifesciencedb.jp/image/small_video_icon.png" rel="nofollow"><img src="http://lifesciencedb.jp/image/small_video_icon.png" alt="http://lifesciencedb.jp/image/small_video_icon.png" /></a> 、<a href="http://togotv.dbcls.jp/20090307.html#p01" rel="nofollow">【使い方参考動画2】</a><a href="http://lifesciencedb.jp/image/small_video_icon.png" rel="nofollow"><img src="http://lifesciencedb.jp/image/small_video_icon.png" alt="http://lifesciencedb.jp/image/small_video_icon.png" /></a></li>
<li>1. <a href="http://www.ncbi.nlm.nih.gov/geo/" rel="nofollow">http://www.ncbi.nlm.nih.gov/geo/</a>を開きます。</li>
<li>2.「<a href="http://www.ncbi.nlm.nih.gov/gds/" rel="nofollow">DataSets</a>」に自分の検索したいキーワードを入力します。</li>
<li>3. 今回は例として「<a href="http://ja.wikipedia.org/wiki/%E3%82%B2%E3%83%95%E3%82%A3%E3%83%81%E3%83%8B%E3%83%96" rel="nofollow">Gefitinib</a>」を検索してみましょう。入力終了後、「GO」をクリックします。</li>
<li>4. GEOに登録されているマイクロアレイ実験のなかから「Gefitinib」に関連する（と思われる）データが表示されます。</li>
<li>5. 検索結果の<a href="http://www.ncbi.nlm.nih.gov/sites/GDSbrowser?acc=GDS2298" rel="nofollow">アクセッション番号（今回は GDS2298）</a>をクリックすると、解析用の「データセットブラウザ」が開きます。</li>
<li>6. 「Expression profiles」をクリックすると、<a href="http://www.ncbi.nlm.nih.gov/sites/entrez?db=geo&amp;cmd=search&amp;term=GDS2298" rel="nofollow"> この実験データセットにおける個々の遺伝子発現状況を検索できるページ</a>に飛びます。</li>
<li>7. 検索窓に表示されているアクセッション番号の後に続けて遺伝子名を追加すると、この実験データセット内におけるその遺伝子の発現データが検索できます。</li>
<li>8. 「データセットブラウザ」の「Data Analysis Tools」では詳細なデータ解析が可能です。</li>
<li>9. 「Find gene name or symbol:」のところに自分の興味ある遺伝子名を入れてみましょう。</li>
<li>10. 「Find genes that are up/down for this condition(s):」の「GO」をクリックするとどのような遺伝子がヒットするでしょうか。</li>
<li>11. 「Compare 2 sets of samples」では2群間で発現に差のある遺伝子を（統計学的に）検索できます。step1で発現量の違いを検出する方法を設定します。step.2で比較する2群の設定をします。step.3の「Query Group A vs. B」をクリックすると、検索が始まります。</li>
<li>12. 「Cluster heatmaps」では、マイクロアレイデータ解析でよく用いられるヒートマップでのデータ表示が行なえます。分類方法としてHierarchical、Partitional (K-means/K-medians)、By location on chromosomeの3種類が選べますが、それぞれどのようにデータが分類されるか試してみましょう。</li>
<li>13.  「Experiment design and value distribution」では実験データにおける発現の分布を参照できます。これにより、各サンプルのデータが互いに比較可能か（実験上のミスがないか）チェックすることができます。</li></ul>

<div class="jumpmenu"><a href="#navigator">&uarr;</a></div><h3 id="content_1_8"><a id="a83d5bfe" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#a83d5bfe" title="a83d5bfe">_</a> 【発展編・その1】GEOを使って、自分の興味のある遺伝子の（ある実験条件下における）発現状況を調べる  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li><a href="http://togotv.dbcls.jp/20090213.html#p01" rel="nofollow">【使い方参考動画】</a><a href="http://lifesciencedb.jp/image/small_video_icon.png" rel="nofollow"><img src="http://lifesciencedb.jp/image/small_video_icon.png" alt="http://lifesciencedb.jp/image/small_video_icon.png" /></a></li>
<li>1. <a href="http://www.ncbi.nlm.nih.gov/geo/" rel="nofollow">http://www.ncbi.nlm.nih.gov/geo/</a>を開きます。</li>
<li>2.「Gene profiles」に自分の検索したい遺伝子名を入力します。</li>
<li>3. 今回は例として「<a href="http://www.google.co.jp/search?hl=ja&amp;q=Nanog%E9%81%BA%E4%BC%9D%E5%AD%90" rel="nofollow">nanog</a>」という遺伝子を検索してみましょう。入力終了後、「GO」をクリックします。</li>
<li>4. GEOに登録されている様々な実験条件で行なわれたマイクロアレイ実験における「nanog」遺伝子の発現データが表示されます。</li>
<li>5. 検索結果の右端にある画像をクリックすると、<a href="http://www.ncbi.nlm.nih.gov/geo/gds/profileGraph.cgi?&amp;dataset=DEAryz&amp;dataset=yyyzzz$&amp;gmin=5173.000000&amp;gmax=11680.000000&amp;absc=&amp;gds=2294&amp;idref=161072_at&amp;annot=Nanog" rel="nofollow">発現データの詳細をみる</a>ことができます。</li>
<li>6. 「Display values」をクリックすると、発現値を一覧できます。</li>
<li>7. <a href="http://www.ncbi.nlm.nih.gov/sites/GDSbrowser?acc=GDS2294" rel="nofollow">このサンプル</a>では、nanogはどういう細胞のどういう実験条件で発現が増減しているか調べてみましょう。</li>
<li>8. ページ下部の「samples」に列挙された<a href="http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM130365" rel="nofollow">リンク</a>をクリックすると、そのサンプル（一枚のマイクロアレイ）の詳細を閲覧できます。</li>
<li>9. <a href="http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM130365" rel="nofollow">リンク先のページ</a>の中ほどにある<a href="http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE5583" rel="nofollow">「series」のリンク</a>をクリックすると、この実験全体の詳細情報が見られます。</li>
<li>10. <a href="http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE5583" rel="nofollow">この実験全体の詳細情報ページ</a>の下部にある<a href="ftp://ftp.ncbi.nih.gov/pub/geo/DATA/SeriesMatrix/GSE5583/" rel="nofollow">「Series Matrix File(s)」</a>をクリックすると、この実験の正規化補正済みのマイクロアレイデータをダウンロードすることができます。</li></ul>

<div class="jumpmenu"><a href="#navigator">&uarr;</a></div><h3 id="content_1_9"><a id="ze44dc22" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#ze44dc22" title="ze44dc22">_</a> 【発展編・その2】GEOを使って、自分の興味のあるマイクロアレイ実験データセットを検索&amp;生データをダウンロードする  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li><a href="http://togotv.dbcls.jp/20081218.html#p01" rel="nofollow">【使い方参考動画】</a><a href="http://lifesciencedb.jp/image/small_video_icon.png" rel="nofollow"><img src="http://lifesciencedb.jp/image/small_video_icon.png" alt="http://lifesciencedb.jp/image/small_video_icon.png" /></a></li>
<li>1. <a href="http://www.ncbi.nlm.nih.gov/geo/" rel="nofollow">http://www.ncbi.nlm.nih.gov/geo/</a>を開きます。</li>
<li>2. 画面中央の「Platforms」をクリックします。</li>
<li>3. <a href="http://www.informatics.jax.org/javawi2/servlet/WIFetch?page=imageSummaryByMrk&amp;key=25000&amp;imageType=8" rel="nofollow">Platform(マイクロアレイの種類)の一覧画面が現れる</a>ので、上部の「FIND PLATFORM」をクリックします。</li>
<li>4. <a href="http://www.ncbi.nlm.nih.gov/geo/query/browse.cgi?mode=findplatform" rel="nofollow">platformの検索画面</a>が現れるので、「Company name」に「Affymetrix」、「organism」に「Homo sapiens」を選択し、「FIND PLATFORM」をクリックします。</li>
<li>5. <a href="http://www.ncbi.nlm.nih.gov/geo/query/browse.cgi?mode=foundplatform" rel="nofollow">Affymetrixのヒトのマイクロアレイの検索結果</a>が表示されるので、中程にある「Affymetrix <span class="noexists">GeneChip<a href="http://MotDB.DBCLS.jp/?cmd=edit&amp;page=GeneChip&amp;refer=AJACS26%2Fhono">?</a></span> Human Genome U133 Plus 2.0 Array」の左端にある<a href="http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GPL570" rel="nofollow">「GPL570」というID</a>をクリックします。</li>
<li>6. <a href="http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GPL570" rel="nofollow">表示された画面</a>の真ん中あたりにある「series」下の「More...」をクリックすると、登録されているデータセットを閲覧できます。</li>
<li>7. ブラウザの検索ボタンなどを使って「reprogramming」という単語を検索するとどういうデータがヒットするでしょうか？</li>
<li>8. ヒットしたデータの左端にあるIDをクリックすると、<a href="http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE9832" rel="nofollow">そのデータセットの詳細情報</a>が閲覧できます</li>
<li>9. ページ下部の「Download family」の中にある「Series Matrix File(s)」をクリックすると正規化済みのデータのダウンロードリンクが表示されます。</li>
<li>10. ページ最下部の「Supplementary file」にあるリンクから生データをダウンロードすることができます。</li>
<li>11. 自分の研究テーマに近い、また興味のあるマイクロアレイデータが利用可能か検索してみましょう。</li></ul>

<div class="jumpmenu"><a href="#navigator">&uarr;</a></div><h3 id="content_1_10"><a id="rdfd50d4" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#rdfd50d4" title="rdfd50d4"><span class="sanchor">_</span></a> 【参考2】<a href="http://lifesciencedb.jp/geo/" rel="nofollow">遺伝子発現バンク(GEO)目次、通称「GEO目次」</a>  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li><a href="http://togotv.dbcls.jp/20080623.html#p01" rel="nofollow">使い方参考動画</a> <a href="http://lifesciencedb.jp/image/small_video_icon.png" rel="nofollow"><img src="http://lifesciencedb.jp/image/small_video_icon.png" alt="http://lifesciencedb.jp/image/small_video_icon.png" /></a></li>
<li>NCBI GEO を日本語のインターフェイスで快適に使い、データの全容を俯瞰するための仕組み</li>
<li>検索が便利！</li></ul>

<div class="jumpmenu"><a href="#navigator">&uarr;</a></div><h3 id="content_1_11"><a id="zef09660" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#zef09660" title="zef09660"><span class="sanchor">_</span></a> <a href="http://david.abcc.ncifcrf.gov/" rel="nofollow"><span style="font-size:20px;display:inline-block;line-height:130%;text-indent:0px">DAVID: The Database for Annotation, Visualization and Integrated Discovery</span></a>  </h3>
<p><span style="color:green">マイクロアレイデータの生物学的な解釈</span></p>
<p><a href="http://david.abcc.ncifcrf.gov/" rel="nofollow">http://david.abcc.ncifcrf.gov/</a></p>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>マイクロアレイ実験の一般的な目的は、実験条件によって得られたある遺伝子群の発現が生物学的にどういう意味を持つかを考えることです。
<div class="img_margin" style="text-align:left"><a href="http://MotDB.DBCLS.jp/?plugin=attach&amp;refer=AJACS14%2Fthecla&amp;openfile=microarray.analysis.005.png" title="microarray.analysis.005.png"><img src="http://MotDB.DBCLS.jp/?plugin=ref&amp;page=AJACS14%2Fthecla&amp;src=microarray.analysis.005.png" alt="microarray.analysis.005.png" title="microarray.analysis.005.png" width="410" height="242" /></a></div>
</li>
<li>今回は、その方法の一つとして、マイクロアレイの結果に<a href="http://www.google.co.jp/url?sa=t&amp;source=web&amp;cd=4&amp;ved=0CEEQFjAD&amp;url=http%3A%2F%2Fja.wikipedia.org%2Fwiki%2F%25E9%2581%25BA%25E4%25BC%259D%25E5%25AD%2590%25E3%2582%25AA%25E3%2583%25B3%25E3%2583%2588%25E3%2583%25AD%25E3%2582%25B8%25E3%2583%25BC&amp;ei=ve9QTd6XMtG6cbeW1KUH&amp;usg=AFQjCNF8U-O4ktlMGoR9DNC0wKltmbjtmw" rel="nofollow">Gene Ontology</a>の用語を付与することで、生物学的な解釈を行います。</li>
<li>【参考動画】<a href="http://togotv.dbcls.jp/20090925.html#p01" rel="nofollow">DAVIDを使ってマイクロアレイデータを解析する</a><a href="http://lifesciencedb.jp/image/small_video_icon.png" rel="nofollow"><img src="http://lifesciencedb.jp/image/small_video_icon.png" alt="http://lifesciencedb.jp/image/small_video_icon.png" /></a></li></ul>

<div class="jumpmenu"><a href="#navigator">&uarr;</a></div><h3 id="content_1_12"><a id="z6529d62" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#z6529d62" title="z6529d62">_</a> マイクロアレイデータの準備  </h3>
<p>サンプルデータとして、<a href="http://www.ncbi.nlm.nih.gov/geo/" rel="nofollow">NCBI GEO</a>より取得した公共の遺伝子発現データを用います。このデータは、ある実験の前後の2群間で有意に発現減少した遺伝子群のリストです。</p>
<div class="img_margin" style="text-align:left"><a href="http://MotDB.DBCLS.jp/?plugin=attach&amp;refer=AJACS24%2Fhono&amp;openfile=110208_IDlist.txt" title="2011/02/07 15:51:39 31.6KB"><img src="image/file.png" width="20" height="20" alt="file" style="border-width:0px" />110208_IDlist.txt</a></div>

<p>（右クリックして「名前を付けてリンク先を保存」してください。）
<br class="spacer" />
このデータは、どのような実験から得られたデータなのか、どのように解釈できるのかをDAVIDを使って考察してみましょう！</p>

<div class="jumpmenu"><a href="#navigator">&uarr;</a></div><h3 id="content_1_13"><a id="y04a402a" href="http://MotDB.DBCLS.jp/?AJACS26%2Fhono#y04a402a" title="y04a402a">_</a> 【実習3】DAVIDを用いて、発現データの結果を生物学的に解釈する  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>1. 上部メニューの「Start Analysis」をクリックします。</li>
<li>2. 画面左側バーで、probe IDリストをコピペ or ファイルを指定します。</li>
<li>3. リストのIDの種類タイプを選択します。 … 今回は、「AFFY_ID」と「Gene List」</li>
<li>4. Submit List をクリックするとリストが読み込まれます。</li>
<li>5. アップロードしたリストは、左側バーの「List Manager」で「Uploaded List_1」として保存されています。削除やrenameもできます。</li>
<li>6. 解析を続けます。真ん中の「Functional Annotation Tool」をクリックします。</li>
<li>7. 「Gene Ontology」をクリックすると、Gene Ontologyを用いた解析の細かいメニューが表示されます。</li>
<li>8. 今回は、GOTERM_BP_FAT (BP=Biological Process)に注目します。その右の「Chart」をクリックすると結果がポップアップされます。</li>
<li>9. P-value を2回クリックしてp-valueが小さい（統計的に有意である）順にしてみましょう … p-value小さい順は、一度やればしばらく覚えているので、次からはしばらくは必要ないです
<a name="plugin_fold_anchor1"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor1')"><p>結果</p>
</div>
<div class="plugin_fold_body"><div class="img_margin" style="text-align:left"><a href="http://MotDB.DBCLS.jp/?plugin=attach&amp;refer=AJACS24%2Fhono&amp;openfile=david_go_bp.png" title="david_go_bp.png"><img src="http://MotDB.DBCLS.jp/?plugin=ref&amp;page=AJACS24%2Fhono&amp;src=david_go_bp.png" alt="david_go_bp.png" title="david_go_bp.png" width="989" height="833" /></a></div>

</div></li>
<li>[応用編] Pathways &gt; KEGG_PATHWAY や Tissue Expression &gt; UP_TISSUE なども見てみましょう。生物学的にどういうことが言えるでしょうか。</li></ul>
	</div>
