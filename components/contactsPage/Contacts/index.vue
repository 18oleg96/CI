<template>
  	<div class="blockContacts">
		<div class="backgroundImgContacts">
	  		<img src="~/assets/images/say.png" alt="say" class="backgroundImgContactsSay">
	  		<img src="~/assets/images/hello.png" alt="hello"> 
		</div>
		<div class="backgroundSquare" />
		<div class="blockContactsMailTel">
	  	<a href="tel:+78692678537" class="blockContactsTel">
			+7 (863) 267-85-37
		</a>
		<div class="dividerContacts">
			<Divider />
		</div>
	  	<a href="mailto:manager@cinet.ru" class="blockContactsMail">
			manager@cinet.ru
	  	</a>
		</div>
		<div class="blockContactsLinks">
		  <a href="#" class="blockContactsLinkSocial">
			<img src="~/assets/images/telegramContacts.png" alt="Telegram" >
		  </a>
		  <a href="#" class="blockContactsLinkSocial">
			<img src="~/assets/images/vkContacts.png" alt="VK"> 
		  </a>
		  <a href="#" class="blockContactsLinkSocial">
			<img src="~/assets/images/twitterContacts.png" alt="Twitter">
		  </a>
		</div>
  	</div>
</template>

<script>
import Divider from "~/components/uikit/Divider";

export default {
	components: {
		Divider,
	},
}
</script>

<style lang="scss">
	@import './styles';
</style>
