<div class="col-4">
        <div class="row" style="height: 100px;"></div>
        <style>
          .botBadge {
            width: 80%;
            border-radius: 25px;
            transition: .2s;
          }
          .sidebarButtonInvite {
            width: 80%;
            border-radius: 25px;
            border: 2px solid #E74C3C;
            color: #E74C3C;
            transition: .2s;
            background-color: rgba(231, 76, 60, 0.2);
          }
          .sidebarButtonInvite:hover {
            color: #E74C3C;
            transition: .2s;
            transform: scale(.950)
          }
          .sidebarButtonVote {
            width: 80%;
            border-radius: 25px;
            border: 2px solid #2ECC71;
            color: #2ECC71;
            transition: .2s;
            background-color: rgba(46, 204, 113, 0.2);
          }
          .sidebarButtonVote:hover {
            color: #2ECC71;
            transition: .2s;
            transform: scale(.950)
          }
          .blankDiv {
            height: 10px;
            with: 25px;
          }
          html {
            overflow-x: hidden;
          }
          .botInfo {
            background-color: rgba(256,256,256,.2);
            color: white;
          }
          .sidebarButtonSupport {
            width: 80%;
            border-radius: 25px;
            border: 2px solid #A569BD;
            color: #A569BD;
            transition: .2s;
            background-color: rgba(165, 105, 189, 0.2);
          }
          .sidebarButtonSupport:hover {
            color: #A569BD;
            transition: .2s;
            transform: scale(.950)
          }
          .sidebarButtonSite {
            width: 80%;
            border-radius: 25px;
            border: 2px solid #F1948A;
            color: #F1948A;
            transition: .2s;
            background-color: rgba(241, 148, 138, 0.2);
          }
          .sidebarButtonSite:hover {
            color: #F1948A;
            transition: .2s;
            transform: scale(.950)
          }
        </style>
        <h3 style="color: white;">
          <i class="fad fa-fingerprint"></i>&nbsp; MoodOnMusic<b style="opacity: .6; font-size: 50%;">#4400</b>
        </h3>
        
		
		
		
        
        
        
        
        
        
        
        
        
		
		
		
				
        
        
        
        
          
            <style>
              .online { background-color: rgba(236, 240, 241, 0.2); border: 2px solid #ECF0F1; }
              .online:hover { background-color: rgba(34, 205, 68, 0.3); border: 2px solid #22CD44; }
            </style>
            
            <div class="blankDiv"></div>
          
          
          
          
        
				
				<div class="blankDiv"></div>
        
        
				
				
		
        
        <h3 style="color: white;">
          <i class="fad fa-list"></i>&nbsp; Bot Bilgileri
        </h3>
        <hr style="border: 1px solid #3a3b3c;">
        
          <a class="btn botInfo" style="text-align: left; color: white; border: 2px solid white; border-bottom: none; border-radius: 10px 10px 0px 0px; width: 100%;">&nbsp;&nbsp; <i class="fad fa-crown"></i>&nbsp; Geliştirici &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<i style="font-size: 75%;" class="fad fa-arrow-alt-right"></i>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Farkedilmem<b style="opacity: .6; font-size: 70%;">#7392</b></a><br>
          <a class="btn botInfo" style="text-align: left; color: white; border: 2px solid white; border-bottom: none; border-top: none; border-radius: 0px; width: 100%;">&nbsp;&nbsp; <i class="fad fa-question-circle"></i>&nbsp; Prefix &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<i style="font-size: 75%;" class="fad fa-arrow-alt-right"></i>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :</a><br>
          <a class="btn botInfo" style="text-align: left; color: white; border: 2px solid white; border-bottom: none; border-top: none; border-radius: 0px; width: 100%;">&nbsp;&nbsp; <i class="fad fa-books"></i>&nbsp; Kütüphane &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<i style="font-size: 75%;" class="fad fa-arrow-alt-right"></i>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; discord.js</a><br>
          <a class="btn botInfo" style="text-align: left; color: white; border: 2px solid white; border-top: none; border-radius: 0px 0px 10px 10px; width: 100%;">&nbsp;&nbsp; <i class="fad fa-tags"></i>&nbsp; Etiketler &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<i style="font-size: 75%;" class="fad fa-arrow-alt-right"></i>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <b style="font-size: 70%;">Müzik</b></a><br>
        
        
        
        
        
        <hr style="border: 1px solid #3a3b3c;">
        
				<div class="blankDiv"></div>
				
				<div class="blankDiv"></div>
		
		<script>
		$(document).ready(function(){
		  $('.copyButton').click(function(){
			alert("Kopyalandı!");
			var $temp = $("<input>");
			$("body").append($temp);
			$temp.val($('.copyButton').attr('id')).select();
			document.execCommand("copy");
			$temp.remove();
		  });
		});
		</script>
        
				<div class="modal fade" id="botURL" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
					<div class="modal-dialog modal-dialog-centered" role="document">
						<div class="modal-content" style="text-align: left; border-radius: 20px; background-color: rgba(58,59,60,1);">
							<div class="modal-header" style="border-bottom: 2px solid rgba(68,69,70,1);">
								<h5 class="modal-title" style="color: white;" id="exampleModalCenterTitle"><i style="color: #48C9B0;" class="fad fa-link"></i>&nbsp; MoodOnMusic <b style="opacity: .4;">için Özel URL</b></h5>
								<button type="button" class="close" data-dismiss="modal" aria-label="Close">
									<style>#closeButton:select { outline: none; } #closeButton { transition: .2; }</style>
									<i id="closeButton" area-hidden="true" class="fad fa-times-circle" style="transition: .2; color: white;"></i>
								</button>
							</div>
							<div class="modal-body" style="color: white;">
								<label for="specialURL"><i class="fad fa-network-wired"></i>&nbsp; Özel URL: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <b id="errorMsg" style="color: rgb(244, 208, 63); display: none;"></b></label>
								<div class="input-group mb-2">
									<div class="input-group-prepend">
										<div class="input-group-text">codamey.net/@</div>
									</div>
									<input type="text" value="" class="form-control" id="specialURL">
								</div>
								<br>
								<a id="URLbutton" class="btn btn-danger"><i class="fad fa-link"></i>&nbsp; Özel URL Ayarla</a> &nbsp; <a href="/bot/760745375673352202/urlRemove" class="btn btn-primary"><i class="fad fa-trash-alt"></i>&nbsp; Özel URL Kaldır</a>
								<script>
								$(document).ready(function(){
									$('#errorMsg').hide();
									$('#specialURL').change(function(){
										$('#errorMsg').hide(100);
									});
									$('#URLbutton').click(function(){
										if (!$('#specialURL').val()) { $('#errorMsg').text('Hata: Bir URL yazınız.'); $('#errorMsg').show(100); return; };
										window.location.href = "/bot/760745375673352202/url/" + $('#specialURL').val();
									});
								});
								</script>
							</div>
						</div>
					</div>
				</div>
				
        <div class="modal fade" id="editBot" style="text-align: left;" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
          <div class="modal-dialog" role="document">
            <div class="modal-content" style="border-radius: 20px; background-color: rgba(58,59,60,1);">
              <div class="modal-header" style="border-bottom: 2px solid rgba(68,69,70,1);">
                <h5 class="modal-title" style="color: white;" id="exampleModalCenterTitle"><i style="color: #48C9B0;" class="fad fa-edit"></i>&nbsp; MoodOnMusic<b style="opacity: .4;">#4400</b> &nbsp;<span class="badge" style="background-color: rgba(72,201,176,.5);">Botu Düzenle</span></h5>
                <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                  <style>#closeButton:select { outline: none; } #closeButton { transition: .2; }</style>
                  <i id="closeButton" area-hidden="true" class="fad fa-times-circle" style="transition: .2; color: white;"></i>
                </button>
              </div>
              <div class="modal-body" style="color: white;">
                <!--  <hr style="background-color: rgba(68,69,70,1);">  -->
                <form method="POST">
                  <div class="row">
                    <div class="col">
                      <h7>Prefix:</h7>
                      <input value=":" class="form-control" type="text" name="botPrefix" id="botPrefix" min-length="1" max-length="10" required="true">
                    </div>
                    <div class="col">
                      <h7>Kütüphane:</h7>
                      <select class="custom-select" name="botLibrary" id="botLibrary" required="true">
                        <option value="discord.js" selected="">discord.js</option>
                        <option value="discord.js">discord.js</option>
                        <option value="2">Two</option>
                        <option value="3">Three</option>
                        <option value="discordcr">discordcr</option>
                        <option value="Nyxx">Nyxx</option>
                        <option value="Discord.Net">Discord.Net</option>
                        <option value="DSharpPlus">DSharpPlus</option>
                        <option value="Nostrum">Nostrum</option>
                        <option value="coxir">coxir</option>
                        <option value="DiscordGo">DiscordGo</option>
                        <option value="Discord4J">Discord4J</option>
                        <option value="Javacord">Javacord</option>
                        <option value="JDA">JDA</option>
                        <option value="discord.js">discord.js</option>
                        <option value="Eris">Eris</option>
                        <option value="Discordia">Discordia</option>
                        <option value="RestCord">RestCord</option>
                        <option value="Yasmin">Yasmin</option>
                        <option value="disco">disco</option>
                        <option value="discord.py">discord.py</option>
                        <option value="discordrb">discordrb</option>
                        <option value="serenity">serenity</option>
                        <option value="SwiftDiscord">SwiftDiscord</option>
                        <option value="Sword">Sword</option>
                        <option value="Other">Other</option>
                      </select>
                    </div>
                  </div>
                  <hr>
                  <div class="row">
                    <div class="col">
                      <h7>Etiketler:</h7>
                      <select style="height: 40px;" class="custom-select" name="botTags" id="botTags" required="true" multiple="">
                        <option value="Diğer" disabled="" selected="">Seçiniz...</option>
                        <option value="Müzik">Müzik</option>
                        <option value="Moderasyon">Moderasyon</option>
                        <option value="Eğlence">Eğlence</option>
                        <option value="Diğer">Diğer</option>
                      </select>
                    </div>
                    <div class="col">
                      <h7>Afiş URL:</h7>
                      <input disabled="" value="https://cdn.wallpapersafari.com/74/18/ohNFH8.jpg" type="text" name="botBannerURL" id="botBannerURL" class="form-control" required="true">
                    </div>
                  </div>
                  <hr>
                  <div class="row">
                    <div class="col">
                      <h7>İnternet Sitesi:</h7>
                      <input value="" class="form-control" type="text" name="botSite" id="botSite">
                    </div>
                    <div class="col">
                      <h7>Destek Sunucusu:</h7>
                      <input value="Müzik" class="form-control" type="text" name="botSupport" id="botSupport">
                    </div>
                  </div>
                  <hr>
                  <div style="padding: 0px 15px;" class="row">
                    <h7>Kısa Açıklama:</h7>
                    <input value="En iyi müzik botunu denemek istemez misin?" type="text" minlength="5" maxlength="45" name="botShortDesc" id="botShortDesc" required="true" class="form-control">
                  </div>
                  <hr>
                  <div style="padding: 0px 15px;" class="row">
                    <h7>Uzun Açıklama:</h7>
                    <textarea name="botLongDesc" id="botLongDesc" class="form-control" style="height: 130px;" minlength="100" maxlength="5000" required="true">&lt;article class="entity-content"&gt;
&lt;section class="entity-content__section entity-header"&gt;
&lt;div class="entity-header__info"&gt;
&lt;div class="entity-header__vertical-wrapper"&gt;
&lt;div class="entity-header__vertical-wrapper-section entity-header__details"&gt;
&lt;div class="base__Flex-sc-1f9zlm1-0 base__Column-sc-1f9zlm1-2 UgVug dOWREt"&gt;
&lt;h1 class="entity-header__name-wrapper"&gt;&lt;span class="base__StyledText-sc-1f9zlm1-4 ktRGBq entity-header__name"&gt;----BOT HAKKINDA----&lt;br /&gt;&lt;br /&gt;MoodOnMusic&lt;/span&gt;&lt;/h1&gt;
MoodOnMusic tamamen sizin kaliteli m&amp;uuml;zik dinlemeniz i&amp;ccedil;in kodlandı. Yakında onaylanacak bu bot sizler i&amp;ccedil;in &amp;uuml;cretsiz olarak hizmet veriyor. Pro s&amp;uuml;r&amp;uuml;mleri olmamak ile birlikte herkes eşit durumdadır.&lt;br /&gt;&lt;br /&gt;7/24 aktif olan bu bot sadece g&amp;uuml;nl&amp;uuml;k g&amp;uuml;ncellemelerde 1-2 dakikalık kesinti olacaktır. Şuanda sadece T&amp;uuml;rk&amp;ccedil;e diliyle hizmet veriyoruz. İleride daha fazla dil eklenecektir.&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/section&gt;
&lt;hr class="horizontal-separator entity-content__divider" /&gt;
&lt;section class="entity-content__section entity-sidebar"&gt;
&lt;div class="entity-sidebar__overview"&gt;
&lt;div class="entity-table"&gt;
&lt;h1 class="entity-table__cell"&gt;&amp;nbsp;&lt;/h1&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/section&gt;
&lt;section class="entity-content__section entity-user-content"&gt;&lt;main class="entity-content__description"&gt;
&lt;div class="content"&gt;
&lt;p&gt;Desteğe ihtiyacınız olursa discord sunucumuza gelerek yardım alabilirsiniz.&lt;/p&gt;
&lt;p&gt;&lt;img src="https://cdn.glitch.com/32e90c1d-3a41-4b29-a97a-1626d7c89749%2FTOP-GG-Tantm.gif?v=1615970064711" alt="" width="577" height="325" /&gt;&lt;br /&gt;-Kaliteli olduğu i&amp;ccedil;in kullanılır.&lt;br /&gt;En hızlı şekilde m&amp;uuml;zik dinlemek i&amp;ccedil;in kullanılır.&lt;br /&gt;-Tamamen T&amp;uuml;rk&amp;ccedil;e olduğu i&amp;ccedil;in kullanılır.&lt;br /&gt;-Pro s&amp;uuml;r&amp;uuml;m&amp;uuml; olmadan herkese adaletli davranıldığı i&amp;ccedil;in kullanılır.&lt;br /&gt;-Hi&amp;ccedil;bir gelir kaynağı olmadan hizmet verildiği i&amp;ccedil;in kullanılır.&lt;/p&gt;
&lt;section class="entity-content__section entity-sidebar"&gt;
&lt;div class="entity-sidebar__misc"&gt;&lt;main class="entity-content__description"&gt;
&lt;div class="content"&gt;&lt;main class="entity-content__description"&gt;
&lt;div class="content"&gt;
&lt;h3&gt;&lt;strong&gt;&lt;em&gt;-------------&lt;/em&gt;&lt;/strong&gt;&lt;strong&gt;&lt;em&gt;Komutlar&lt;/em&gt;&lt;/strong&gt;&lt;strong&gt;&lt;em&gt;-------------&lt;/em&gt;&lt;/strong&gt;&lt;/h3&gt;
&lt;br /&gt;
&lt;div class="table-responsive"&gt;
&lt;table class="table color-bordered-table red-bordered-table"&gt;
&lt;thead&gt;
&lt;tr&gt;
&lt;th style="width: 180px;"&gt;Komut&lt;/th&gt;
&lt;th&gt;A&amp;ccedil;ıklama&lt;/th&gt;
&lt;/tr&gt;
&lt;/thead&gt;
&lt;tbody&gt;
&lt;tr&gt;
&lt;td&gt;:yardım&lt;/td&gt;
&lt;td&gt;Ana komutları g&amp;ouml;sterir.&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;td&gt;:&amp;ccedil;al&lt;/td&gt;
&lt;td&gt;M&amp;uuml;zik oynatmak i&amp;ccedil;in kullanılır.&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;td&gt;:&amp;ccedil;alanşarkı&lt;/td&gt;
&lt;td&gt;Şuanda oynatılan şarkıyı g&amp;ouml;sterir.&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;td&gt;:duraklat&lt;/td&gt;
&lt;td&gt;Oynatılan şarkıyı durdurur.&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;td&gt;:devamet&lt;/td&gt;
&lt;td&gt;Durdurulan şarkıyı devam ettirir.&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;td&gt;:ge&amp;ccedil;&lt;/td&gt;
&lt;td&gt;Bir m&amp;uuml;ziği dinlemek istemediğinizde bu komut ile ge&amp;ccedil;ebilirsiniz.&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;td&gt;:kuyruk&lt;/td&gt;
&lt;td&gt;A&amp;ccedil;ılan t&amp;uuml;m şarkıların sırasını g&amp;ouml;sterir.&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;td&gt;:ayrıl&lt;/td&gt;
&lt;td&gt;M&amp;uuml;zik dinlemeyi bırakmak i&amp;ccedil;in kullanılır.&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;td&gt;:bot-bilgi&lt;/td&gt;
&lt;td&gt;Bot istatistiklerine erişmek i&amp;ccedil;in kullanılır.&lt;/td&gt;
&lt;/tr&gt;
&lt;/tbody&gt;
&lt;/table&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/main&gt;&lt;/div&gt;
&lt;/main&gt;&lt;/div&gt;
&lt;/section&gt;
&lt;/div&gt;
&lt;/main&gt;&lt;/section&gt;
&lt;/article&gt;</textarea>
                  </div>
                  <hr>
                  <center><button type="submit" class="btn btn-success"><i class="fad fa-save"></i>&nbsp; Kaydet</button></center>
                </form>
              </div>
            </div>
          </div>
        </div>
        
        
      </div>
