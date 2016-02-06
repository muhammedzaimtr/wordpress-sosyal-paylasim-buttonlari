# WORDPRESS SOSYAL MEDYA PAYLAŞIM BUTONLARI

Tek yapmanız gereken projelerinize aşağıdaki kodları eklemek

#head etiketleri arasına gelecek kısım:
<!-- 
<link rel="stylesheet" href="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/master/css/font-awesome.min.css" media="screen" title="no title" charset="utf-8">
-->

#body etiketleri arasına gelecek kısım:

<!-- 
<div class="paylas">
			<a class="facebook-btn" href="//www.facebook.com/sharer.php?u=<?php echo urlencode( get_permalink() ); ?>" target="_blank"><?php _e( 'Share', 'wptouch-pro' ); ?></a>
			<a class="twitter-btn" href="//twitter.com/intent/tweet?source=wptouchpro3&text=<?php echo htmlspecialchars( urlencode( html_entity_decode( get_the_title() . ' - ' ) ) ); ?>&url=<?php echo urlencode( get_permalink() ); ?>" target="_blank"><?php _e( 'Tweet', 'wptouch-pro' ); ?></a>
			<a class="pinterest-btn" href="//pinterest.com/pin/create/button/?url=<?php echo urlencode( get_permalink() ); ?>" target="_blank"><?php _e( 'Pin', 'wptouch-pro' ); ?></a>
			<a class="email-btn" href="mailto:?subject=<?php echo rawurlencode( get_the_title() ); ?>&body=<?php echo rawurlencode( get_permalink() ); ?>"><?php  _e( 'Mail', 'wptouch-pro' ); ?></a>
		</div>
-->		
	
	
#Çalışmayı Bilgisayarına indir ve istediğin gibi kullan :)

git clone https://github.com/muhammedzaimtr/wordpress-sosyal-paylasim-buttonlari

