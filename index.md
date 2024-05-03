<html>
  <body>
  <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
            window.addEventListener("onEmbeddedMessagingReady", () => {            
				console.log( "Inside Prechat API!!" );
				embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields( { "Order_Number" : "Test123" } );
			});
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D2C0000008oKm',
				'MW_GitHub_OmniFlow',
				'https://wkhlrp--dev04.sandbox.my.site.com/ESWMWGitHubOmniFlow1714734622038',
				{
					scrt2URL: 'https://wkhlrp--dev04.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://wkhlrp--dev04.sandbox.my.site.com/ESWMWGitHubOmniFlow1714734622038/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
