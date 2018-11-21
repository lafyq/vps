<div id="sina_keyword_ad_area2" class="articalContent   newfont_family">
			<p style="margin: 0.7em 0px; padding: 0px; color: rgb(85, 85, 85); font-size: 13px; line-height: 1.4em; font-family: 'Helvetica neue', Helvetica, Arial, sans-serif; font-variant-ligatures: normal; orphans: 2; widows: 2; background-color: rgb(255, 255, 255);">
目前的国内外fq软件已经全线崩溃，国内更有众多软件停止运营，无论付费与免费软件目前均不可使用。一开始本人也是小白一个，但是之前用过各种fq方法，都不是很理想，前些天终于开始搭建自己通道，目前用起来还是很爽的。youtube视频无压力。</p>
<p style="margin: 0.7em 0px; padding: 0px; color: rgb(85, 85, 85); font-size: 13px; line-height: 1.4em; font-family: 'Helvetica neue', Helvetica, Arial, sans-serif; font-variant-ligatures: normal; orphans: 2; widows: 2; background-color: rgb(255, 255, 255);">
<span style="font-weight: 700;">由于搬瓦工在控制面板取消了一键安装Shadowsocks，原来的一键安装的教程不适用了，我们重新整理了用SS脚本的安装方式，也非常的简单，下面开始吧</span></p>
<h2 style="margin: 0.3em 0px; padding: 10px 0px 5px; font-weight: 500; position: relative; color: rgb(85, 85, 85); font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; font-size: 1.8em; line-height: 1.1em; font-variant-ligatures: normal; orphans: 2; widows: 2; background-color: rgb(255, 255, 255);">
第一步、<b>挑选注册适合自己的vps</b></h2>
<div style="margin: 0px; padding: 0px; color: rgb(85, 85, 85); font-family: 'Helvetica neue', Helvetica, Arial, sans-serif; font-size: 13px; font-variant-ligatures: normal; orphans: 2; widows: 2; background-color: rgb(255, 255, 255);">
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
经过再三选择之后我选择了搬瓦工VPS，我们就以搬瓦工VPS为基础，教大家购买VPS，搭建自己的SS，科学上网。目前搬瓦工VPS机房已经达到7个，分别是New
York [USNY_2]，Los Angeles, California (DC1 QNET)，Los Angeles,
California (DC2 MCOM)，Fremont, California，Phoenix,
Arizona，Jacksonville, Florida，Amsterdam,
Netherlands。没有特殊需求下，建议使用洛杉矶（Los
Angeles）。常规最低配置$19.99/年，相当于每月1美金多一点。不过经常缺货，需要的要赶机会。</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4255" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/fdhdfghdfdgh/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/fdhdfghdfdgh.png?w=632&amp;h=192" data-orig-size="987,300" data-comments-opened="1" data-image-meta="{" data-image-title="fdhdfghdfdgh" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/fdhdfghdfdgh.png?w=632&amp;h=192?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/fdhdfghdfdgh.png?w=632&amp;h=192?w=632" src="https://kxswhome.files.wordpress.com/2018/03/fdhdfghdfdgh.png?w=632&amp;h=192" real_src="https://kxswhome.files.wordpress.com/2018/03/fdhdfghdfdgh.png?w=632&amp;h=192" alt="" width="632" height="192" srcset="https://kxswhome.files.wordpress.com/2018/03/fdhdfghdfdgh.png?w=632&amp;h=192 632w, https://kxswhome.files.wordpress.com/2018/03/fdhdfghdfdgh.png?w=150&amp;h=46 150w, https://kxswhome.files.wordpress.com/2018/03/fdhdfghdfdgh.png?w=300&amp;h=91 300w, https://kxswhome.files.wordpress.com/2018/03/fdhdfghdfdgh.png?w=768&amp;h=233 768w, https://kxswhome.files.wordpress.com/2018/03/fdhdfghdfdgh.png 987w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<h3 style="margin: 0.3em 0px; padding: 5px 0px; font-weight: 500; font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; font-size: 1.6em;">
1、选择需要的VPS方案</h3>
<h4 style="margin: 0.3em 0px; padding: 5px 0px; font-weight: 500; font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; position: relative; border-bottom-color: rgb(240, 240, 240); font-size: 1.4em; line-height: 1.2em;">
<span style="font-weight: 700;">A、年19.99方案（KVM架构），价格最优！</span></h4>
<ul style="margin-left: 18px; padding: 0px; font-size: 1em; line-height: 1.4em; border: 0px none; overflow: visible; margin-top: 10px !important; margin-right: 0px !important; margin-bottom: 22px !important;">
<li style="margin: 0px; padding: 2px 0px 0px; border: 0px none; overflow: visible;">
内存：512MB</li>
<li style="margin: 0px; padding: 2px 0px 0px; border: 0px none; overflow: visible;">
硬盘：10GB SSD</li>
<li style="margin: 0px; padding: 2px 0px 0px; border: 0px none; overflow: visible;">
流量：500GB/月</li>
<li style="margin: 0px; padding: 2px 0px 0px; border: 0px none; overflow: visible;">
价格：$2.99/月（年$19.99）</li>
</ul>
<div style="margin: 0px; padding: 0px;">
<a href="http://rebrand.ly/bandw25ead" target="_blank">&gt;&gt;年$19.99直达方案通道（KVM架构6机房）</a>（都可以使用6%优惠码，享受6%优惠）</div>
<h4 style="margin: 0.3em 0px; padding: 5px 0px; font-weight: 500; font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; position: relative; border-bottom-color: rgb(240, 240, 240); font-size: 1.4em; line-height: 1.2em;">
<span style="font-weight: 700;">B、年$29.99方案（洛杉矶CN2），稳定性更好和国内访问更快。</span></h4>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
（19.99美元每年的方案经常缺货，可以选择年$29.99CN2方案）</p>
<ul style="margin-left: 18px; padding: 0px; font-size: 1em; line-height: 1.4em; border: 0px none; overflow: visible; margin-top: 10px !important; margin-right: 0px !important; margin-bottom: 22px !important;">
<li style="margin: 0px; padding: 2px 0px 0px; border: 0px none; overflow: visible;">
内存：512MB</li>
<li style="margin: 0px; padding: 2px 0px 0px; border: 0px none; overflow: visible;">
硬盘：10GB SSD</li>
<li style="margin: 0px; padding: 2px 0px 0px; border: 0px none; overflow: visible;">
流量：500GB/月</li>
<li style="margin: 0px; padding: 2px 0px 0px; border: 0px none; overflow: visible;">
价格：年$29.99</li>
</ul>
<div style="margin: 0px; padding: 0px;">
<a href="https://rebrand.ly/bandw02a9a" target="_blank">&gt;&gt;年$29.99直达方案通道（KVM洛杉矶CN2）</a>（使用6%优惠码，相当于每月不到2.35美金）</div>
<div style="margin: 0px; padding: 0px;">
<h4 style="margin: 0.3em 0px; padding: 5px 0px; font-weight: 500; font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; position: relative; border-bottom-color: rgb(240, 240, 240); font-size: 1.4em; line-height: 1.2em;">
<span style="font-weight: 700;">C、</span>&nbsp;<wbr>半年29.99方案（洛杉矶CN2），<span style="font-weight: 700;">配置更强，空间更大。</span></h4>
<div style="margin: 0px; padding: 0px;">
<div style="margin: 0px; padding: 0px;">
<div style="margin: 0px; padding: 0px;">
<ul style="margin-left: 18px; padding: 0px; font-size: 1em; line-height: 1.4em; border: 0px none; overflow: visible; margin-top: 10px !important; margin-right: 0px !important; margin-bottom: 22px !important;">
<li style="margin: 0px; padding: 2px 0px 0px; border: 0px none; overflow: visible;">
内存：1024MB</li>
<li style="margin: 0px; padding: 2px 0px 0px; border: 0px none; overflow: visible;">
硬盘：20GB SSD</li>
<li style="margin: 0px; padding: 2px 0px 0px; border: 0px none; overflow: visible;">
流量：1000GB/月</li>
<li style="margin: 0px; padding: 2px 0px 0px; border: 0px none; overflow: visible;">
价格：$29.99/半年（年$49）</li>
</ul>
<div style="margin: 0px; padding: 0px;"><a href="https://rebrand.ly/bandw5c178" target="_blank">&gt;&gt;直达方案通道（KVM洛杉矶CN2）</a>（都可以使用6%优惠码，享受6%优惠）</div>
</div>
</div>
</div>
</div>
<h3 style="margin: 0.3em 0px; padding: 5px 0px; font-weight: 500; font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; font-size: 1.6em;">
2、选择付款周期和机房位置</h3>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
点击直达链接后，我们会跳转到下图所示的界面。根据图中指示，方案选择年付29.99美金的CN2线路即可，机房位置有洛杉矶的DC3或者DC8机房，默认DC3即可。洛杉矶位于美国西部，国内访问速度相对较快，掉包也比较少。</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4256" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/fdhfghfgsss/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/fdhfghfgsss.png?w=632&amp;h=351" data-orig-size="632,351" data-comments-opened="1" data-image-meta="{" data-image-title="fdhfghfgsss" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/fdhfghfgsss.png?w=632&amp;h=351?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/fdhfghfgsss.png?w=632&amp;h=351?w=632" src="https://kxswhome.files.wordpress.com/2018/03/fdhfghfgsss.png?w=632&amp;h=351" real_src="https://kxswhome.files.wordpress.com/2018/03/fdhfghfgsss.png?w=632&amp;h=351" alt="" width="632" height="351" srcset="https://kxswhome.files.wordpress.com/2018/03/fdhfghfgsss.png 632w, https://kxswhome.files.wordpress.com/2018/03/fdhfghfgsss.png?w=150&amp;h=83 150w, https://kxswhome.files.wordpress.com/2018/03/fdhfghfgsss.png?w=300&amp;h=167 300w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<h3 style="margin: 0.3em 0px; padding: 5px 0px; font-weight: 500; font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; font-size: 1.6em;">
3、核对价格和填写优惠码</h3>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
点击 Add to Cart 按钮后，我们会跳转到下图所示界面。根据图中指示，我们首先输入下面的最新优惠码，然后点击 Validate
Code 按钮验证优惠码，最后点击 Checkout 按钮继续。</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
搬瓦工最新可用优惠码：当前我们可以使用优惠码“&nbsp;<wbr><span style="font-weight: 700;">BWH1ZBPVK</span>&nbsp;<wbr>”节省6%的费用</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4257" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/gfdgdgd/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/gfdgdgd.png?w=632&amp;h=247" data-orig-size="632,247" data-comments-opened="1" data-image-meta="{" data-image-title="gfdgdgd" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/gfdgdgd.png?w=632&amp;h=247?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/gfdgdgd.png?w=632&amp;h=247?w=632" src="https://kxswhome.files.wordpress.com/2018/03/gfdgdgd.png?w=632&amp;h=247" real_src="https://kxswhome.files.wordpress.com/2018/03/gfdgdgd.png?w=632&amp;h=247" alt="" width="632" height="247" srcset="https://kxswhome.files.wordpress.com/2018/03/gfdgdgd.png 632w, https://kxswhome.files.wordpress.com/2018/03/gfdgdgd.png?w=150&amp;h=59 150w, https://kxswhome.files.wordpress.com/2018/03/gfdgdgd.png?w=300&amp;h=117 300w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<h3 style="margin: 0.3em 0px; padding: 5px 0px; font-weight: 500; font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; font-size: 1.6em;">
4、登录或者注册搬瓦工账户</h3>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
点击 Checkout 按钮后，我们会跳转到下图所示界面。根据图中指示，我们首先填写个人信息，有账户的直接点击 Click here
to login 按钮登录。填写完毕后点击 Update 更新，然后选择Alipay付款方式，然后在 I have read and
agree the Terms of Service 前面打钩，最后点击 Complete Order 按钮继续。</p>
<blockquote style="margin: 0px; padding: 2px 12px; color: rgb(136, 136, 136); background: rgb(241, 241, 241);">
<p style="margin: 0.7em 0px; padding: 0px; color: rgb(85, 85, 85); font-size: 1em; line-height: 1.4em;">
注意：国家请务必选择China，不要乱选择，这样可以避免以后被暂停服务。</p>
</blockquote>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4258" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/bfdhghgf/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/bfdhghgf.png?w=632" data-orig-size="594,535" data-comments-opened="1" data-image-meta="{" data-image-title="bfdhghgf" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/bfdhghgf.png?w=632?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/bfdhghgf.png?w=632?w=594" src="https://kxswhome.files.wordpress.com/2018/03/bfdhghgf.png?w=632" real_src="https://kxswhome.files.wordpress.com/2018/03/bfdhghgf.png?w=632" alt="" srcset="https://kxswhome.files.wordpress.com/2018/03/bfdhghgf.png 594w, https://kxswhome.files.wordpress.com/2018/03/bfdhghgf.png?w=150 150w, https://kxswhome.files.wordpress.com/2018/03/bfdhghgf.png?w=300 300w" sizes="(max-width: 594px) 100vw, 594px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<h3 style="margin: 0.3em 0px; padding: 5px 0px; font-weight: 500; font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; font-size: 1.6em;">
5、使用支付宝付款</h3>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
点击 Complete Order 按钮后，我们会跳转到下图所示界面。根据图中指示，我们点击 Pay now 按钮继续。</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4221" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/20161127165832-1-1-1-4/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/20161127165832-1-1-11.png?w=632" data-orig-size="454,116" data-comments-opened="1" data-image-meta="{" data-image-title="20161127165832-1-1-1" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/20161127165832-1-1-11.png?w=632?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/20161127165832-1-1-11.png?w=632?w=454" src="https://kxswhome.files.wordpress.com/2018/03/20161127165832-1-1-11.png?w=632" real_src="https://kxswhome.files.wordpress.com/2018/03/20161127165832-1-1-11.png?w=632" alt="" srcset="https://kxswhome.files.wordpress.com/2018/03/20161127165832-1-1-11.png 454w, https://kxswhome.files.wordpress.com/2018/03/20161127165832-1-1-11.png?w=150 150w, https://kxswhome.files.wordpress.com/2018/03/20161127165832-1-1-11.png?w=300 300w" sizes="(max-width: 454px) 100vw, 454px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
点击 Pay now 按钮后，我们会跳转到下图所示界面。根据下图指示，我们使用手机支付宝扫码付款或者电脑登录支付宝进行付款。</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4259" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/fdhfgjkghjgh/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/fdhfgjkghjgh.png?w=632&amp;h=738" data-orig-size="632,738" data-comments-opened="1" data-image-meta="{" data-image-title="fdhfgjkghjgh" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/fdhfgjkghjgh.png?w=632&amp;h=738?w=257" data-large-file="https://kxswhome.files.wordpress.com/2018/03/fdhfgjkghjgh.png?w=632&amp;h=738?w=632" src="https://kxswhome.files.wordpress.com/2018/03/fdhfgjkghjgh.png?w=632&amp;h=738" real_src="https://kxswhome.files.wordpress.com/2018/03/fdhfgjkghjgh.png?w=632&amp;h=738" alt="" width="632" height="738" srcset="https://kxswhome.files.wordpress.com/2018/03/fdhfgjkghjgh.png 632w, https://kxswhome.files.wordpress.com/2018/03/fdhfgjkghjgh.png?w=128&amp;h=150 128w, https://kxswhome.files.wordpress.com/2018/03/fdhfgjkghjgh.png?w=257&amp;h=300 257w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
使用支付宝付款，付完款后，邮箱不久就能收到新的VPS信息，包含root帐号密码 端口号</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
当然也可以再后台进行操作：点击 My Services 查看VPS</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4223" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/6364628971513173602787479-1-1-4/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/6364628971513173602787479-1-1.png?w=632&amp;h=358" data-orig-size="1044,591" data-comments-opened="1" data-image-meta="{" data-image-title="6364628971513173602787479-1-1" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/6364628971513173602787479-1-1.png?w=632&amp;h=358?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/6364628971513173602787479-1-1.png?w=632&amp;h=358?w=632" src="https://kxswhome.files.wordpress.com/2018/03/6364628971513173602787479-1-1.png?w=632&amp;h=358" real_src="https://kxswhome.files.wordpress.com/2018/03/6364628971513173602787479-1-1.png?w=632&amp;h=358" alt="" width="632" height="358" srcset="https://kxswhome.files.wordpress.com/2018/03/6364628971513173602787479-1-1.png?w=632&amp;h=358 632w, https://kxswhome.files.wordpress.com/2018/03/6364628971513173602787479-1-1.png?w=150&amp;h=85 150w, https://kxswhome.files.wordpress.com/2018/03/6364628971513173602787479-1-1.png?w=300&amp;h=170 300w, https://kxswhome.files.wordpress.com/2018/03/6364628971513173602787479-1-1.png?w=768&amp;h=435 768w, https://kxswhome.files.wordpress.com/2018/03/6364628971513173602787479-1-1.png?w=1024&amp;h=580 1024w, https://kxswhome.files.wordpress.com/2018/03/6364628971513173602787479-1-1.png 1044w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
&nbsp;<wbr></p>
<h2 style="margin: 0.3em 0px; padding: 10px 0px 5px; font-weight: 500; position: relative; font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; font-size: 1.8em; line-height: 1.1em;">
第二步、开始搭建Shadowsocks</h2>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
由于之前搬瓦工曾经取消了一键安装Shadowsocks的按钮(部分现已恢复），我们特意给出了三种安装Shadowsocks的方法。方法一和方法二（没有一键安装SS按钮也可以）就是搬瓦工后台一键安装Shadowsocks的方法，更适合小白适用，简单快捷。方法三是采用SSH，用脚本方式安装Shadowsocks，更适合进阶用户使用，或者搬瓦工抽风取消一键安装的时候。还在犹豫什么？选择自己适用的方式，开始吧。</p>
<h3 style="margin: 0.3em 0px; padding: 5px 0px; font-weight: 500; font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; font-size: 1.6em;">
<span style="font-weight: 700;">方法一：搬瓦工后台一键安装Shadowsocks（小白适用）</span></h3>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
1、进入管理后台，点击进入控制面板</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4224" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/asdasdasdasds/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/asdasdasdasds.png?w=632&amp;h=197" data-orig-size="1001,312" data-comments-opened="1" data-image-meta="{" data-image-title="asdasdasdasds" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/asdasdasdasds.png?w=632&amp;h=197?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/asdasdasdasds.png?w=632&amp;h=197?w=632" src="https://kxswhome.files.wordpress.com/2018/03/asdasdasdasds.png?w=632&amp;h=197" real_src="https://kxswhome.files.wordpress.com/2018/03/asdasdasdasds.png?w=632&amp;h=197" alt="" width="632" height="197" srcset="https://kxswhome.files.wordpress.com/2018/03/asdasdasdasds.png?w=632&amp;h=197 632w, https://kxswhome.files.wordpress.com/2018/03/asdasdasdasds.png?w=150&amp;h=47 150w, https://kxswhome.files.wordpress.com/2018/03/asdasdasdasds.png?w=300&amp;h=94 300w, https://kxswhome.files.wordpress.com/2018/03/asdasdasdasds.png?w=768&amp;h=239 768w, https://kxswhome.files.wordpress.com/2018/03/asdasdasdasds.png 1001w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
2、找到左侧的Shadowsocks server，出现如下画面，点击安装</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4225" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/5402342sdfdf34/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/5402342sdfdf34.png?w=632&amp;h=457" data-orig-size="949,686" data-comments-opened="1" data-image-meta="{" data-image-title="5402342sdfdf34" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/5402342sdfdf34.png?w=632&amp;h=457?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/5402342sdfdf34.png?w=632&amp;h=457?w=632" src="https://kxswhome.files.wordpress.com/2018/03/5402342sdfdf34.png?w=632&amp;h=457" real_src="https://kxswhome.files.wordpress.com/2018/03/5402342sdfdf34.png?w=632&amp;h=457" alt="" width="632" height="457" srcset="https://kxswhome.files.wordpress.com/2018/03/5402342sdfdf34.png?w=632&amp;h=457 632w, https://kxswhome.files.wordpress.com/2018/03/5402342sdfdf34.png?w=150&amp;h=108 150w, https://kxswhome.files.wordpress.com/2018/03/5402342sdfdf34.png?w=300&amp;h=217 300w, https://kxswhome.files.wordpress.com/2018/03/5402342sdfdf34.png?w=768&amp;h=555 768w, https://kxswhome.files.wordpress.com/2018/03/5402342sdfdf34.png 949w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
3、安装很快，基本不到1分钟就可以完成，出现如下画面，点击返回</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4226" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/gdgsdfdffesgdfg/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/gdgsdfdffesgdfg.png?w=632&amp;h=382" data-orig-size="1141,690" data-comments-opened="1" data-image-meta="{" data-image-title="gdgsdfdffesgdfg" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/gdgsdfdffesgdfg.png?w=632&amp;h=382?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/gdgsdfdffesgdfg.png?w=632&amp;h=382?w=632" src="https://kxswhome.files.wordpress.com/2018/03/gdgsdfdffesgdfg.png?w=632&amp;h=382" real_src="https://kxswhome.files.wordpress.com/2018/03/gdgsdfdffesgdfg.png?w=632&amp;h=382" alt="" width="632" height="382" srcset="https://kxswhome.files.wordpress.com/2018/03/gdgsdfdffesgdfg.png?w=632&amp;h=382 632w, https://kxswhome.files.wordpress.com/2018/03/gdgsdfdffesgdfg.png?w=150&amp;h=91 150w, https://kxswhome.files.wordpress.com/2018/03/gdgsdfdffesgdfg.png?w=300&amp;h=181 300w, https://kxswhome.files.wordpress.com/2018/03/gdgsdfdffesgdfg.png?w=768&amp;h=464 768w, https://kxswhome.files.wordpress.com/2018/03/gdgsdfdffesgdfg.png?w=1024&amp;h=619 1024w, https://kxswhome.files.wordpress.com/2018/03/gdgsdfdffesgdfg.png 1141w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
4、好了，就可以看到自己的SS信息了。如果想修改，还可以点后面的按钮修改。</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4227" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/sfasdfa/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/sfasdfa.png?w=632&amp;h=258" data-orig-size="685,280" data-comments-opened="1" data-image-meta="{" data-image-title="sfasdfa" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/sfasdfa.png?w=632&amp;h=258?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/sfasdfa.png?w=632&amp;h=258?w=632" src="https://kxswhome.files.wordpress.com/2018/03/sfasdfa.png?w=632&amp;h=258" real_src="https://kxswhome.files.wordpress.com/2018/03/sfasdfa.png?w=632&amp;h=258" alt="" width="632" height="258" srcset="https://kxswhome.files.wordpress.com/2018/03/sfasdfa.png?w=632&amp;h=258 632w, https://kxswhome.files.wordpress.com/2018/03/sfasdfa.png?w=150&amp;h=61 150w, https://kxswhome.files.wordpress.com/2018/03/sfasdfa.png?w=300&amp;h=123 300w, https://kxswhome.files.wordpress.com/2018/03/sfasdfa.png 685w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
以上设置完毕，可以直接跳到第三步，设置SS客户端。</p>
<h3 style="margin: 0.3em 0px; padding: 5px 0px; font-weight: 500; font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; font-size: 1.6em;">
<span style="font-weight: 700;">方法二：直接输入网址的一键SS，类似方法一</span><span style="font-weight: 700;">（小白适用）</span></h3>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
1、如果后台没有一键SS按钮，我们只需要登陆到搬瓦工后台，然后在浏览器输入如下链接，并回车：</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<a href="https://kiwivm.64clouds.com/preloader.php?load=/main-exec.php?mode=extras_shadowsocks" target="_blank">https://kiwivm.64clouds.com/preloader.php?load=/main-exec.php?mode=extras_shadowsocks</a></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4228" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/dfafgfgs/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/dfafgfgs.jpg?w=632&amp;h=355" data-orig-size="1214,682" data-comments-opened="1" data-image-meta="{" data-image-title="DFAFGFGS" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/dfafgfgs.jpg?w=632&amp;h=355?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/dfafgfgs.jpg?w=632&amp;h=355?w=632" src="https://kxswhome.files.wordpress.com/2018/03/dfafgfgs.jpg?w=632&amp;h=355" real_src="https://kxswhome.files.wordpress.com/2018/03/dfafgfgs.jpg?w=632&amp;h=355" alt="" width="632" height="355" srcset="https://kxswhome.files.wordpress.com/2018/03/dfafgfgs.jpg?w=632&amp;h=355 632w, https://kxswhome.files.wordpress.com/2018/03/dfafgfgs.jpg?w=150&amp;h=84 150w, https://kxswhome.files.wordpress.com/2018/03/dfafgfgs.jpg?w=300&amp;h=169 300w, https://kxswhome.files.wordpress.com/2018/03/dfafgfgs.jpg?w=768&amp;h=431 768w, https://kxswhome.files.wordpress.com/2018/03/dfafgfgs.jpg?w=1024&amp;h=575 1024w, https://kxswhome.files.wordpress.com/2018/03/dfafgfgs.jpg 1214w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
然后就可以看到SS安装界面了，如下图</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4229" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/dfgdfgsdf/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/dfgdfgsdf.jpg?w=632&amp;h=231" data-orig-size="898,328" data-comments-opened="1" data-image-meta="{" data-image-title="dfgdfgsdf" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/dfgdfgsdf.jpg?w=632&amp;h=231?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/dfgdfgsdf.jpg?w=632&amp;h=231?w=632" src="https://kxswhome.files.wordpress.com/2018/03/dfgdfgsdf.jpg?w=632&amp;h=231" real_src="https://kxswhome.files.wordpress.com/2018/03/dfgdfgsdf.jpg?w=632&amp;h=231" alt="" width="632" height="231" srcset="https://kxswhome.files.wordpress.com/2018/03/dfgdfgsdf.jpg?w=632&amp;h=231 632w, https://kxswhome.files.wordpress.com/2018/03/dfgdfgsdf.jpg?w=150&amp;h=55 150w, https://kxswhome.files.wordpress.com/2018/03/dfgdfgsdf.jpg?w=300&amp;h=110 300w, https://kxswhome.files.wordpress.com/2018/03/dfgdfgsdf.jpg?w=768&amp;h=281 768w, https://kxswhome.files.wordpress.com/2018/03/dfgdfgsdf.jpg 898w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
2、点击安装就可以了。安装很快，基本不到1分钟就可以完成，出现如下画面，点击返回</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4230" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/fgvhgkjh/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/fgvhgkjh.png?w=632&amp;h=382" data-orig-size="1141,690" data-comments-opened="1" data-image-meta="{" data-image-title="fgvhgkjh" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/fgvhgkjh.png?w=632&amp;h=382?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/fgvhgkjh.png?w=632&amp;h=382?w=632" src="https://kxswhome.files.wordpress.com/2018/03/fgvhgkjh.png?w=632&amp;h=382" real_src="https://kxswhome.files.wordpress.com/2018/03/fgvhgkjh.png?w=632&amp;h=382" alt="" width="632" height="382" srcset="https://kxswhome.files.wordpress.com/2018/03/fgvhgkjh.png?w=632&amp;h=382 632w, https://kxswhome.files.wordpress.com/2018/03/fgvhgkjh.png?w=150&amp;h=91 150w, https://kxswhome.files.wordpress.com/2018/03/fgvhgkjh.png?w=300&amp;h=181 300w, https://kxswhome.files.wordpress.com/2018/03/fgvhgkjh.png?w=768&amp;h=464 768w, https://kxswhome.files.wordpress.com/2018/03/fgvhgkjh.png?w=1024&amp;h=619 1024w, https://kxswhome.files.wordpress.com/2018/03/fgvhgkjh.png 1141w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
3、好了，就可以看到自己的SS信息了。如果想修改，还可以点后面的按钮修改。</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4231" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/gnnmbn/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/gnnmbn.png?w=632&amp;h=258" data-orig-size="685,280" data-comments-opened="1" data-image-meta="{" data-image-title="gnnmbn" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/gnnmbn.png?w=632&amp;h=258?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/gnnmbn.png?w=632&amp;h=258?w=632" src="https://kxswhome.files.wordpress.com/2018/03/gnnmbn.png?w=632&amp;h=258" real_src="https://kxswhome.files.wordpress.com/2018/03/gnnmbn.png?w=632&amp;h=258" alt="" width="632" height="258" srcset="https://kxswhome.files.wordpress.com/2018/03/gnnmbn.png?w=632&amp;h=258 632w, https://kxswhome.files.wordpress.com/2018/03/gnnmbn.png?w=150&amp;h=61 150w, https://kxswhome.files.wordpress.com/2018/03/gnnmbn.png?w=300&amp;h=123 300w, https://kxswhome.files.wordpress.com/2018/03/gnnmbn.png 685w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<h3 style="margin: 0.3em 0px; padding: 5px 0px; font-weight: 500; font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; font-size: 1.6em;">
<span style="font-weight: 700;">方法三：SSH脚本方式安装Shadowsocks（进阶版用户适用）</span></h3>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
1、获取SSH地址、端口和Root密码</p>
<div style="margin: 0px; padding: 0px;">
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4232" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/cvnbvmnvb/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/cvnbvmnvb.png?w=632&amp;h=327" data-orig-size="687,356" data-comments-opened="1" data-image-meta="{" data-image-title="cvnbvmnvb" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/cvnbvmnvb.png?w=632&amp;h=327?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/cvnbvmnvb.png?w=632&amp;h=327?w=632" src="https://kxswhome.files.wordpress.com/2018/03/cvnbvmnvb.png?w=632&amp;h=327" real_src="https://kxswhome.files.wordpress.com/2018/03/cvnbvmnvb.png?w=632&amp;h=327" alt="" width="632" height="327" srcset="https://kxswhome.files.wordpress.com/2018/03/cvnbvmnvb.png?w=632&amp;h=327 632w, https://kxswhome.files.wordpress.com/2018/03/cvnbvmnvb.png?w=150&amp;h=78 150w, https://kxswhome.files.wordpress.com/2018/03/cvnbvmnvb.png?w=300&amp;h=155 300w, https://kxswhome.files.wordpress.com/2018/03/cvnbvmnvb.png 687w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
</div>
<div style="margin: 0px; padding: 0px;"></div>
<div style="margin: 0px; padding: 0px;"></div>
<div style="margin: 0px; padding: 0px;">点击My
Services后我们来到下图界面</div>
<div style="margin: 0px; padding: 0px;">
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4233" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/006ub5wezy7fpufghntc7amp690-5/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/006ub5wezy7fpufghntc7amp690.jpg?w=632&amp;h=182" data-orig-size="690,199" data-comments-opened="1" data-image-meta="{" data-image-title="006Ub5Wezy7fPufGHNtc7amp690" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/006ub5wezy7fpufghntc7amp690.jpg?w=632&amp;h=182?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/006ub5wezy7fpufghntc7amp690.jpg?w=632&amp;h=182?w=632" src="https://kxswhome.files.wordpress.com/2018/03/006ub5wezy7fpufghntc7amp690.jpg?w=632&amp;h=182" real_src="https://kxswhome.files.wordpress.com/2018/03/006ub5wezy7fpufghntc7amp690.jpg?w=632&amp;h=182" alt="" width="632" height="182" srcset="https://kxswhome.files.wordpress.com/2018/03/006ub5wezy7fpufghntc7amp690.jpg?w=632&amp;h=182 632w, https://kxswhome.files.wordpress.com/2018/03/006ub5wezy7fpufghntc7amp690.jpg?w=150&amp;h=43 150w, https://kxswhome.files.wordpress.com/2018/03/006ub5wezy7fpufghntc7amp690.jpg?w=300&amp;h=87 300w, https://kxswhome.files.wordpress.com/2018/03/006ub5wezy7fpufghntc7amp690.jpg 690w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
</div>
<div style="margin: 0px; padding: 0px;">这里我们点击KiwiVM Control
Panel后我们会跳转到下图界面，找到IP地址和SSH端口，我们还缺少SSH密码</div>
<div style="margin: 0px; padding: 0px;">
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4234" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/ggsdasa/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/ggsdasa.png?w=632&amp;h=173" data-orig-size="1127,308" data-comments-opened="1" data-image-meta="{" data-image-title="ggsdasa" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/ggsdasa.png?w=632&amp;h=173?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/ggsdasa.png?w=632&amp;h=173?w=632" src="https://kxswhome.files.wordpress.com/2018/03/ggsdasa.png?w=632&amp;h=173" real_src="https://kxswhome.files.wordpress.com/2018/03/ggsdasa.png?w=632&amp;h=173" alt="" width="632" height="173" srcset="https://kxswhome.files.wordpress.com/2018/03/ggsdasa.png?w=632&amp;h=173 632w, https://kxswhome.files.wordpress.com/2018/03/ggsdasa.png?w=150&amp;h=41 150w, https://kxswhome.files.wordpress.com/2018/03/ggsdasa.png?w=300&amp;h=82 300w, https://kxswhome.files.wordpress.com/2018/03/ggsdasa.png?w=768&amp;h=210 768w, https://kxswhome.files.wordpress.com/2018/03/ggsdasa.png?w=1024&amp;h=280 1024w, https://kxswhome.files.wordpress.com/2018/03/ggsdasa.png 1127w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
</div>
<div style="margin: 0px; padding: 0px;">
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
搬瓦工为了用户的安全，要求用户在购买 VPS 后，要自己手动在 KiwiVM 控制面板重置密码，还是在控制面板，如下图。</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4235" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/vxvbxcvxc/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/vxvbxcvxc.png?w=632&amp;h=307" data-orig-size="793,385" data-comments-opened="1" data-image-meta="{" data-image-title="vxvbxcvxc" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/vxvbxcvxc.png?w=632&amp;h=307?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/vxvbxcvxc.png?w=632&amp;h=307?w=632" src="https://kxswhome.files.wordpress.com/2018/03/vxvbxcvxc.png?w=632&amp;h=307" real_src="https://kxswhome.files.wordpress.com/2018/03/vxvbxcvxc.png?w=632&amp;h=307" alt="" width="632" height="307" srcset="https://kxswhome.files.wordpress.com/2018/03/vxvbxcvxc.png?w=632&amp;h=307 632w, https://kxswhome.files.wordpress.com/2018/03/vxvbxcvxc.png?w=150&amp;h=73 150w, https://kxswhome.files.wordpress.com/2018/03/vxvbxcvxc.png?w=300&amp;h=146 300w, https://kxswhome.files.wordpress.com/2018/03/vxvbxcvxc.png?w=768&amp;h=373 768w, https://kxswhome.files.wordpress.com/2018/03/vxvbxcvxc.png 793w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
面板右侧会显示你的 ssh 用户名（即 ip 地址）和 ssh 登陆端口，在重置密码前，你需要先停止 vps，在控制面板右侧点击
“stop” 键停止 vps：</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4236" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/vbfxbxc/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/vbfxbxc.png?w=632&amp;h=292" data-orig-size="760,351" data-comments-opened="1" data-image-meta="{" data-image-title="vbfxbxc" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/vbfxbxc.png?w=632&amp;h=292?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/vbfxbxc.png?w=632&amp;h=292?w=632" src="https://kxswhome.files.wordpress.com/2018/03/vbfxbxc.png?w=632&amp;h=292" real_src="https://kxswhome.files.wordpress.com/2018/03/vbfxbxc.png?w=632&amp;h=292" alt="" width="632" height="292" srcset="https://kxswhome.files.wordpress.com/2018/03/vbfxbxc.png?w=632&amp;h=292 632w, https://kxswhome.files.wordpress.com/2018/03/vbfxbxc.png?w=150&amp;h=69 150w, https://kxswhome.files.wordpress.com/2018/03/vbfxbxc.png?w=300&amp;h=139 300w, https://kxswhome.files.wordpress.com/2018/03/vbfxbxc.png 760w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
然后左侧下方的 “Root password modification” 选项为重置密码，你点击该项，进入如下页面：</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4237" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/dcvxvxc/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/dcvxvxc.png?w=632&amp;h=284" data-orig-size="685,308" data-comments-opened="1" data-image-meta="{" data-image-title="dcvxvxc" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/dcvxvxc.png?w=632&amp;h=284?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/dcvxvxc.png?w=632&amp;h=284?w=632" src="https://kxswhome.files.wordpress.com/2018/03/dcvxvxc.png?w=632&amp;h=284" real_src="https://kxswhome.files.wordpress.com/2018/03/dcvxvxc.png?w=632&amp;h=284" alt="" width="632" height="284" srcset="https://kxswhome.files.wordpress.com/2018/03/dcvxvxc.png?w=632&amp;h=284 632w, https://kxswhome.files.wordpress.com/2018/03/dcvxvxc.png?w=150&amp;h=67 150w, https://kxswhome.files.wordpress.com/2018/03/dcvxvxc.png?w=300&amp;h=135 300w, https://kxswhome.files.wordpress.com/2018/03/dcvxvxc.png 685w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
然后点击 “Generate and set new root password” 按钮重置密码即可：</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4238" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/xcbcvbcv/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/xcbcvbcv.png?w=632&amp;h=285" data-orig-size="692,312" data-comments-opened="1" data-image-meta="{" data-image-title="xcbcvbcv" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/xcbcvbcv.png?w=632&amp;h=285?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/xcbcvbcv.png?w=632&amp;h=285?w=632" src="https://kxswhome.files.wordpress.com/2018/03/xcbcvbcv.png?w=632&amp;h=285" real_src="https://kxswhome.files.wordpress.com/2018/03/xcbcvbcv.png?w=632&amp;h=285" alt="" width="632" height="285" srcset="https://kxswhome.files.wordpress.com/2018/03/xcbcvbcv.png?w=632&amp;h=285 632w, https://kxswhome.files.wordpress.com/2018/03/xcbcvbcv.png?w=150&amp;h=68 150w, https://kxswhome.files.wordpress.com/2018/03/xcbcvbcv.png?w=300&amp;h=135 300w, https://kxswhome.files.wordpress.com/2018/03/xcbcvbcv.png 692w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"><br>

重置密码成功后，<span style="font-weight: 700;">要记得重新启动
VPS</span>&nbsp;<wbr>。这样子才可以使用 xshell 或 putty 等工具进行连接。</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
2、下载putty开始连接</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
下载putty：<a href="https://pan.baidu.com/s/1jI0T5Fw" target="_blank">http://pan.baidu.com/s/1jI0T5Fw</a>或者直接在百度搜putty下载解压运行<span>putty.exe</span>，<img data-attachment-id="4239" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/fxbvnbv/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/fxbvnbv.jpg?w=632" data-orig-size="468,417" data-comments-opened="1" data-image-meta="{" data-image-title="fxbvnbv" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/fxbvnbv.jpg?w=632?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/fxbvnbv.jpg?w=632?w=468" src="https://kxswhome.files.wordpress.com/2018/03/fxbvnbv.jpg?w=632" real_src="https://kxswhome.files.wordpress.com/2018/03/fxbvnbv.jpg?w=632" alt="" srcset="https://kxswhome.files.wordpress.com/2018/03/fxbvnbv.jpg 468w, https://kxswhome.files.wordpress.com/2018/03/fxbvnbv.jpg?w=150 150w, https://kxswhome.files.wordpress.com/2018/03/fxbvnbv.jpg?w=300 300w" sizes="(max-width: 468px) 100vw, 468px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
填入刚才查到的主机地址和端口号，前面图中有介绍，点击打开<img data-attachment-id="4240" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/hgmmv/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/hgmmv.png?w=632&amp;h=168" data-orig-size="675,179" data-comments-opened="1" data-image-meta="{" data-image-title="hgmmv" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/hgmmv.png?w=632&amp;h=168?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/hgmmv.png?w=632&amp;h=168?w=632" src="https://kxswhome.files.wordpress.com/2018/03/hgmmv.png?w=632&amp;h=168" real_src="https://kxswhome.files.wordpress.com/2018/03/hgmmv.png?w=632&amp;h=168" alt="" width="632" height="168" srcset="https://kxswhome.files.wordpress.com/2018/03/hgmmv.png?w=632&amp;h=168 632w, https://kxswhome.files.wordpress.com/2018/03/hgmmv.png?w=150&amp;h=40 150w, https://kxswhome.files.wordpress.com/2018/03/hgmmv.png?w=300&amp;h=80 300w, https://kxswhome.files.wordpress.com/2018/03/hgmmv.png 675w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<div align="left" style="margin: 0px; padding: 0px;">
如果这里有对话框弹出，选择是，然后在全黑的屏幕上输入 root
，回车。等五秒，按提示输入root的密码，密码就是前面刚刚重置的root密码。</div>
<div align="left" style="margin: 0px; padding: 0px;">
copy你的密码，粘贴至putty（粘贴方式为单击鼠标右键，只需要右键单击一次，这里不会显示任何内容，其实是已经输入了），回车。</div>
<div align="left" style="margin: 0px; padding: 0px;"></div>
<div align="left" style="margin: 0px; padding: 0px;">
3、SSR脚本安装正式开始</div>
<div align="left" style="margin: 0px; padding: 0px;"></div>
<div align="left" style="margin: 0px; padding: 0px;">
<div align="left" style="margin: 0px; padding: 0px;">
等到出现root@host~字样，</div>
<div align="left" style="margin: 0px; padding: 0px;">
复制下面脚本第1条命令，回车：</div>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
脚本命令1</p>
<table cellspacing="0" cellpadding="0" style="margin: 0.7em 0px 1.5em; padding: 0px; border-style: solid; border-color: rgb(204, 204, 204); border-image: initial; border-width: 1px 1px 1px 0px; border-spacing: 0px; width: 707px;">
<tbody>
<tr style="border: 0px;">
<td bgcolor="#999999" width="689" height="63" style="margin: 0px; padding: 6px 15px; border-style: solid; border-color: rgb(204, 204, 204); border-image: initial; border-width: 1px 0px 0px 1px;">
<span>wget –no-check-certificate
-O&nbsp;<wbr><span>shadowsocks-all.sh</span><a href="https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh">https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh</a></span></td>
</tr>
</tbody>
</table>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
（备注：<span style="font-weight: 700;">国外服务器运行脚本时容易出错，如出现错误提示 bash:
wget: command not found，可以请在先执行 yum -y install wget
命令。成功后，再执行上面的命令。如果没有出现提示错误，请略过</span>）</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4241" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/fvbbncv/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/fvbbncv.jpg?w=632&amp;h=140" data-orig-size="673,149" data-comments-opened="1" data-image-meta="{" data-image-title="fvbbncv" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/fvbbncv.jpg?w=632&amp;h=140?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/fvbbncv.jpg?w=632&amp;h=140?w=632" src="https://kxswhome.files.wordpress.com/2018/03/fvbbncv.jpg?w=632&amp;h=140" real_src="https://kxswhome.files.wordpress.com/2018/03/fvbbncv.jpg?w=632&amp;h=140" alt="" width="632" height="140" srcset="https://kxswhome.files.wordpress.com/2018/03/fvbbncv.jpg?w=632&amp;h=140 632w, https://kxswhome.files.wordpress.com/2018/03/fvbbncv.jpg?w=150&amp;h=33 150w, https://kxswhome.files.wordpress.com/2018/03/fvbbncv.jpg?w=300&amp;h=66 300w, https://kxswhome.files.wordpress.com/2018/03/fvbbncv.jpg 673w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
等出现了上图显示后，输入第2条脚本命令，回车：</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
脚本命令2</p>
<table cellspacing="0" cellpadding="0" style="margin: 0.7em 0px 1.5em; padding: 0px; border-style: solid; border-color: rgb(204, 204, 204); border-image: initial; border-width: 1px 1px 1px 0px; border-spacing: 0px; width: 707px;">
<tbody>
<tr style="border: 0px;">
<td bgcolor="#999999" width="689" height="63" style="margin: 0px; padding: 6px 15px; border-style: solid; border-color: rgb(204, 204, 204); border-image: initial; border-width: 1px 0px 0px 1px;">
<span>chmod +x&nbsp;<wbr><span>shadowsocks-all.sh</span></span></td>
</tr>
</tbody>
</table>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4242" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/fsdfdsfsdfd/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/fsdfdsfsdfd.jpg?w=632&amp;h=42" data-orig-size="670,45" data-comments-opened="1" data-image-meta="{" data-image-title="fsdfdsfsdfd" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/fsdfdsfsdfd.jpg?w=632&amp;h=42?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/fsdfdsfsdfd.jpg?w=632&amp;h=42?w=632" src="https://kxswhome.files.wordpress.com/2018/03/fsdfdsfsdfd.jpg?w=632&amp;h=42" real_src="https://kxswhome.files.wordpress.com/2018/03/fsdfdsfsdfd.jpg?w=632&amp;h=42" alt="" width="632" height="42" srcset="https://kxswhome.files.wordpress.com/2018/03/fsdfdsfsdfd.jpg?w=632&amp;h=42 632w, https://kxswhome.files.wordpress.com/2018/03/fsdfdsfsdfd.jpg?w=150&amp;h=10 150w, https://kxswhome.files.wordpress.com/2018/03/fsdfdsfsdfd.jpg?w=300&amp;h=20 300w, https://kxswhome.files.wordpress.com/2018/03/fsdfdsfsdfd.jpg 670w" sizes="(max-width: 632px) 100vw, 632px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"><br>

等出现了上图显示后，输入第3条脚本命令，回车：</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
脚本命令3</p>
<table cellspacing="0" cellpadding="0" style="margin: 0.7em 0px 1.5em; padding: 0px; border-style: solid; border-color: rgb(204, 204, 204); border-image: initial; border-width: 1px 1px 1px 0px; border-spacing: 0px; width: 707px;">
<tbody>
<tr style="border: 0px;">
<td bgcolor="#999999" width="689" height="63" style="margin: 0px; padding: 6px 15px; border-style: solid; border-color: rgb(204, 204, 204); border-image: initial; border-width: 1px 0px 0px 1px;">
<span>./<span>shadowsocks-all.sh</span>&nbsp;<wbr>2&gt;&amp;1
| tee&nbsp;<wbr><span>shadowsocks-all.log</span></span></td>
</tr>
</tbody>
</table>
<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0px; overflow: auto; font-family: Monaco, Consolas, 'Courier new', monospace; font-size: 1em;"><img data-attachment-id="4243" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/cvgnvbnvb/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/cvgnvbnvb.jpg?w=632&amp;h=113" data-orig-size="651,116" data-comments-opened="1" data-image-meta="{" data-image-title="cvgnvbnvb" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/cvgnvbnvb.jpg?w=632&amp;h=113?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/cvgnvbnvb.jpg?w=632&amp;h=113?w=632" src="https://kxswhome.files.wordpress.com/2018/03/cvgnvbnvb.jpg?w=632&amp;h=113" real_src="https://kxswhome.files.wordpress.com/2018/03/cvgnvbnvb.jpg?w=632&amp;h=113" alt="" width="632" height="113" srcset="https://kxswhome.files.wordpress.com/2018/03/cvgnvbnvb.jpg?w=632&amp;h=113 632w, https://kxswhome.files.wordpress.com/2018/03/cvgnvbnvb.jpg?w=150&amp;h=27 150w, https://kxswhome.files.wordpress.com/2018/03/cvgnvbnvb.jpg?w=300&amp;h=53 300w, https://kxswhome.files.wordpress.com/2018/03/cvgnvbnvb.jpg 651w" sizes="(max-width: 632px) 100vw, 632px">
出现以上画面，根据需要选择，不懂的话直接选1，或者默认回车
</pre></div>
<div align="left" style="margin: 0px; padding: 0px;"></div>
</div>
<div align="left" style="margin: 0px; padding: 0px;">
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
下面会提示你输入你的SS
SERVER的密码，和端口。不输入就是默认。跑完命令后会出来你的SS客户端的信息。<img data-attachment-id="4244" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/dgfdgdf/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/dgfdgdf.jpg?w=632" data-orig-size="490,166" data-comments-opened="1" data-image-meta="{" data-image-title="dgfdgdf" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/dgfdgdf.jpg?w=632?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/dgfdgdf.jpg?w=632?w=490" src="https://kxswhome.files.wordpress.com/2018/03/dgfdgdf.jpg?w=632" real_src="https://kxswhome.files.wordpress.com/2018/03/dgfdgdf.jpg?w=632" alt="" srcset="https://kxswhome.files.wordpress.com/2018/03/dgfdgdf.jpg 490w, https://kxswhome.files.wordpress.com/2018/03/dgfdgdf.jpg?w=150 150w, https://kxswhome.files.wordpress.com/2018/03/dgfdgdf.jpg?w=300 300w" sizes="(max-width: 490px) 100vw, 490px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
</div>
<div align="left" style="margin: 0px; padding: 0px;">
<img data-attachment-id="4245" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/dbfbdfg/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/dbfbdfg.jpg?w=632" data-orig-size="490,98" data-comments-opened="1" data-image-meta="{" data-image-title="dbfbdfg" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/dbfbdfg.jpg?w=632?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/dbfbdfg.jpg?w=632?w=490" src="https://kxswhome.files.wordpress.com/2018/03/dbfbdfg.jpg?w=632" real_src="https://kxswhome.files.wordpress.com/2018/03/dbfbdfg.jpg?w=632" alt="" srcset="https://kxswhome.files.wordpress.com/2018/03/dbfbdfg.jpg 490w, https://kxswhome.files.wordpress.com/2018/03/dbfbdfg.jpg?w=150 150w, https://kxswhome.files.wordpress.com/2018/03/dbfbdfg.jpg?w=300 300w" sizes="(max-width: 490px) 100vw, 490px"></div>
<div align="left" style="margin: 0px; padding: 0px;">输入后，回车！</div>
<div align="left" style="margin: 0px; padding: 0px;"></div>
<div align="left" style="margin: 0px; padding: 0px;">
<img data-attachment-id="4246" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/dfgdfghfg/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/dfgdfghfg.png?w=632&amp;h=314" data-orig-size="675,335" data-comments-opened="1" data-image-meta="{" data-image-title="dfgdfghfg" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/dfgdfghfg.png?w=632&amp;h=314?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/dfgdfghfg.png?w=632&amp;h=314?w=632" src="https://kxswhome.files.wordpress.com/2018/03/dfgdfghfg.png?w=632&amp;h=314" real_src="https://kxswhome.files.wordpress.com/2018/03/dfgdfghfg.png?w=632&amp;h=314" alt="" width="632" height="314" srcset="https://kxswhome.files.wordpress.com/2018/03/dfgdfghfg.png?w=632&amp;h=314 632w, https://kxswhome.files.wordpress.com/2018/03/dfgdfghfg.png?w=150&amp;h=74 150w, https://kxswhome.files.wordpress.com/2018/03/dfgdfghfg.png?w=300&amp;h=149 300w, https://kxswhome.files.wordpress.com/2018/03/dfgdfghfg.png 675w" sizes="(max-width: 632px) 100vw, 632px"></div>
<div align="left" style="margin: 0px; padding: 0px;">
特别注意，由于iphone端的的wingy目前只支持到cfb，所以我们选择aes-256-cfb，即7 ，回车</div>
<div align="left" style="margin: 0px; padding: 0px;"></div>
<div align="left" style="margin: 0px; padding: 0px;">
<img data-attachment-id="4247" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/fdsfsdfsd-2/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/fdsfsdfsd.jpg?w=632&amp;h=244" data-orig-size="658,254" data-comments-opened="1" data-image-meta="{" data-image-title="fdsfsdfsd" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/fdsfsdfsd.jpg?w=632&amp;h=244?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/fdsfsdfsd.jpg?w=632&amp;h=244?w=632" src="https://kxswhome.files.wordpress.com/2018/03/fdsfsdfsd.jpg?w=632&amp;h=244" real_src="https://kxswhome.files.wordpress.com/2018/03/fdsfsdfsd.jpg?w=632&amp;h=244" alt="" width="632" height="244" srcset="https://kxswhome.files.wordpress.com/2018/03/fdsfsdfsd.jpg?w=632&amp;h=244 632w, https://kxswhome.files.wordpress.com/2018/03/fdsfsdfsd.jpg?w=150&amp;h=58 150w, https://kxswhome.files.wordpress.com/2018/03/fdsfsdfsd.jpg?w=300&amp;h=116 300w, https://kxswhome.files.wordpress.com/2018/03/fdsfsdfsd.jpg 658w" sizes="(max-width: 632px) 100vw, 632px"><br>
这一步按回车继续</div>
<div align="left" style="margin: 0px; padding: 0px;">
然后需要几分钟的安装过程，请耐心等待出现下面的画面！</div>
<div align="left" style="margin: 0px; padding: 0px;">
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4248" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/fdsfasdffds/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/fdsfasdffds.jpg?w=632" data-orig-size="573,261" data-comments-opened="1" data-image-meta="{" data-image-title="fdsfasdffds" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/fdsfasdffds.jpg?w=632?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/fdsfasdffds.jpg?w=632?w=573" src="https://kxswhome.files.wordpress.com/2018/03/fdsfasdffds.jpg?w=632" real_src="https://kxswhome.files.wordpress.com/2018/03/fdsfasdffds.jpg?w=632" alt="" srcset="https://kxswhome.files.wordpress.com/2018/03/fdsfasdffds.jpg 573w, https://kxswhome.files.wordpress.com/2018/03/fdsfasdffds.jpg?w=150 150w, https://kxswhome.files.wordpress.com/2018/03/fdsfasdffds.jpg?w=300 300w" sizes="(max-width: 573px) 100vw, 573px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
请立即copy下来加以保存。</p>
</div>
<div align="left" style="margin: 0px; padding: 0px;">
上面的命令全部回车执行后，如果没有报错，即为执行成功，出现确认提示的时候，输入 y 后，回车即可。</div>
<div align="left" style="margin: 0px; padding: 0px;">
安装完成后，脚本提示如下：</div>
<div align="left" style="margin: 0px; padding: 0px;">
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
Congratulations, Shadowsocks-Python server install completed!<br>
Your Server IP : IP地址<br>
Your Server Port : 端口<br>
Your Password : 密码<br>
Your Encryption Method: aes-256-gcm</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
Your QR Code: (For Shadowsocks Windows, OSX, Android and iOS
clients)<br>
ss://YWVzLTsadsa206YnVkZHkyMD<wbr>A4QDEwNC4yMjQuMTM1Ldfghd<wbr>fgk=<br>
Your QR Code has been saved as a PNG file path:<br>
/root/<span>shadowsocks_python_qr.png</span></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
Welcome to visit:&nbsp;<wbr><a href="https://teddysun.com/486.html">https://teddysun.com/486.html</a><br>

Enjoy it!</p>
</div>
<div align="left" style="margin: 0px; padding: 0px;">
记录保存好你的上述信息：Server IP、Server Port、Password、Encryption Method</div>
<div align="left" style="margin: 0px; padding: 0px;">
这时你的专属ss已经搭好了，开始使用吧。</div>
</div>
<div style="margin: 0px; padding: 0px; color: rgb(85, 85, 85); font-family: 'Helvetica neue', Helvetica, Arial, sans-serif; font-size: 13px; font-variant-ligatures: normal; orphans: 2; widows: 2; background-color: rgb(255, 255, 255);">
<h2 align="left" style="margin: 0.3em 0px; padding: 10px 0px 5px; font-weight: 500; position: relative; font-family: Helveticaneue-Light, 'Helvetica neue Light', 'Helvetica neue', Helvetica, Arial, sans-serif; font-size: 1.8em; line-height: 1.1em;">
第三步、iphone、windows、安卓设置使用</h2>
<div align="left" style="margin: 0px; padding: 0px;">
1、iphone下载wingy（免费的），app store里搜wingy（中国app
store已经下架，可以换到美国账户下载）</div>
<div align="left" style="margin: 0px; padding: 0px;"><a href="https://itunes.apple.com/us/app/wingy-proxy-for-http-s-socks5/id1178584911?mt=8" target="_blank">https://itunes.apple.com/us/app/wingy-proxy-for-http-s-socks5/id1178584911?mt=8</a></div>
<div align="left" style="margin: 0px; padding: 0px;">
点击选择线路–新增线路–shadowsocks–依次填入刚才记录的信息就好–保存–点击连接就可以了</div>
<div align="left" style="margin: 0px; padding: 0px;">这样就翻墙成功了</div>
<div align="left" style="margin: 0px; padding: 0px;">
2、windows下载</div>
<div align="left" style="margin: 0px; padding: 0px;">
windows客户端更新（170925）</div>
<div align="left" style="margin: 0px; padding: 0px;"><a href="https://github.com/shadowsocks/shadowsocks-windows/releases" target="_blank">https://github.com/shadowsocks/shadowsocks-windows/releases</a></div>
<div align="left" style="margin: 0px; padding: 0px;">下载<a href="https://github.com/shadowsocks/shadowsocks-windows/releases/download/4.0.6/Shadowsocks-4.0.6.zip">Shadowsocks-4.0.6.zip</a></div>
<div align="left" style="margin: 0px; padding: 0px;">
<img data-attachment-id="4249" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/dasffdsfsd/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/dasffdsfsd.jpg?w=632" data-orig-size="490,459" data-comments-opened="1" data-image-meta="{" data-image-title="dasffdsfsd" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/dasffdsfsd.jpg?w=632?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/dasffdsfsd.jpg?w=632?w=490" src="https://kxswhome.files.wordpress.com/2018/03/dasffdsfsd.jpg?w=632" real_src="https://kxswhome.files.wordpress.com/2018/03/dasffdsfsd.jpg?w=632" alt="" srcset="https://kxswhome.files.wordpress.com/2018/03/dasffdsfsd.jpg 490w, https://kxswhome.files.wordpress.com/2018/03/dasffdsfsd.jpg?w=150 150w, https://kxswhome.files.wordpress.com/2018/03/dasffdsfsd.jpg?w=300 300w" sizes="(max-width: 490px) 100vw, 490px"></div>
<div align="left" style="margin: 0px; padding: 0px;">
下载解压缩，运行exe</div>
<div align="left" style="margin: 0px; padding: 0px;">
<img data-attachment-id="4250" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/dfsgdfgfd/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/dfsgdfgfd.jpg?w=632" data-orig-size="490,453" data-comments-opened="1" data-image-meta="{" data-image-title="dfsgdfgfd" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/dfsgdfgfd.jpg?w=632?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/dfsgdfgfd.jpg?w=632?w=490" src="https://kxswhome.files.wordpress.com/2018/03/dfsgdfgfd.jpg?w=632" real_src="https://kxswhome.files.wordpress.com/2018/03/dfsgdfgfd.jpg?w=632" alt="" srcset="https://kxswhome.files.wordpress.com/2018/03/dfsgdfgfd.jpg 490w, https://kxswhome.files.wordpress.com/2018/03/dfsgdfgfd.jpg?w=150 150w, https://kxswhome.files.wordpress.com/2018/03/dfsgdfgfd.jpg?w=300 300w" sizes="(max-width: 490px) 100vw, 490px"></div>
<div align="left" style="margin: 0px; padding: 0px;">
填入之前记录的自己的服务器信息，点击确定</div>
<div align="left" style="margin: 0px; padding: 0px;">
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4251" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/fdsfsdfdsdf/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/fdsfsdfdsdf.png?w=632" data-orig-size="200,95" data-comments-opened="1" data-image-meta="{" data-image-title="fdsfsdfdsdf" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/fdsfsdfdsdf.png?w=632?w=200" data-large-file="https://kxswhome.files.wordpress.com/2018/03/fdsfsdfdsdf.png?w=632?w=200" src="https://kxswhome.files.wordpress.com/2018/03/fdsfsdfdsdf.png?w=632" real_src="https://kxswhome.files.wordpress.com/2018/03/fdsfsdfdsdf.png?w=632" alt="" srcset="https://kxswhome.files.wordpress.com/2018/03/fdsfsdfdsdf.png 200w, https://kxswhome.files.wordpress.com/2018/03/fdsfsdfdsdf.png?w=150 150w" sizes="(max-width: 200px) 100vw, 200px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
</div>
<div align="left" style="margin: 0px; padding: 0px;">
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
在电脑右下角任务栏找到ss图标，右键点击，点击启用系统代理就可以了，试试上google吧</p>
</div>
<div align="left" style="margin: 0px; padding: 0px;">
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<img data-attachment-id="4252" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/gfdhjkhkjh/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/gfdhjkhkjh.jpg?w=632" data-orig-size="184,200" data-comments-opened="1" data-image-meta="{" data-image-title="gfdhjkhkjh" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/gfdhjkhkjh.jpg?w=632?w=184" data-large-file="https://kxswhome.files.wordpress.com/2018/03/gfdhjkhkjh.jpg?w=632?w=184" src="https://kxswhome.files.wordpress.com/2018/03/gfdhjkhkjh.jpg?w=632" real_src="https://kxswhome.files.wordpress.com/2018/03/gfdhjkhkjh.jpg?w=632" alt="" srcset="https://kxswhome.files.wordpress.com/2018/03/gfdhjkhkjh.jpg 184w, https://kxswhome.files.wordpress.com/2018/03/gfdhjkhkjh.jpg?w=138 138w" sizes="(max-width: 184px) 100vw, 184px" style="border: 1px solid rgb(238, 238, 238); vertical-align: top; padding: 2px; display: block; max-width: 98%; height: auto;"></p>
</div>
<div align="left" style="margin: 0px; padding: 0px;">
3、android</div>
<div align="left" style="margin: 0px; padding: 0px;">
安卓的客户端可以用ShadowSOCKS（影梭），目前是v4.2.5版本，下载地址如下：</div>
<div align="left" style="margin: 0px; padding: 0px;">
<img data-attachment-id="4253" data-permalink="https://kxsw.home.blog/2018/03/02/jiao_cheng_shou_ba_shou_jiao_ni_yong_ban_wa_gong_vps_da_jian_shu_yu_zi_ji_de_ss_jiao_cheng_ke_xue_sh/fgjhgjkghjk/" data-orig-file="https://kxswhome.files.wordpress.com/2018/03/fgjhgjkghjk.png?w=632&amp;h=313" data-orig-size="730,361" data-comments-opened="1" data-image-meta="{" data-image-title="fgjhgjkghjk" data-image-description="" data-medium-file="https://kxswhome.files.wordpress.com/2018/03/fgjhgjkghjk.png?w=632&amp;h=313?w=300" data-large-file="https://kxswhome.files.wordpress.com/2018/03/fgjhgjkghjk.png?w=632&amp;h=313?w=632" src="https://kxswhome.files.wordpress.com/2018/03/fgjhgjkghjk.png?w=632&amp;h=313" real_src="https://kxswhome.files.wordpress.com/2018/03/fgjhgjkghjk.png?w=632&amp;h=313" alt="" width="632" height="313" srcset="https://kxswhome.files.wordpress.com/2018/03/fgjhgjkghjk.png?w=632&amp;h=313 632w, https://kxswhome.files.wordpress.com/2018/03/fgjhgjkghjk.png?w=150&amp;h=74 150w, https://kxswhome.files.wordpress.com/2018/03/fgjhgjkghjk.png?w=300&amp;h=148 300w, https://kxswhome.files.wordpress.com/2018/03/fgjhgjkghjk.png 730w" sizes="(max-width: 632px) 100vw, 632px"></div>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
<a href="https://github.com/shadowsocks/shadowsocks-android/releases">https://github.com/shadowsocks/shadowsocks-android/releases</a></p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
类似苹果手机，添加配置文件就可以了。</p>
<p style="margin: 0.7em 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">
好了，一切都搞定，开始科学上网吧，是不是很简单呢！</p>
</div>							
```html
	</div>
```