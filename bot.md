<html>
  <body>
  <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D2C0000008oKm',
				'MW_BOT',
				'https://wkhlrp--dev04.sandbox.my.site.com/ESWMWBOT1714737671666',
				{
					scrt2URL: 'https://wkhlrp--dev04.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://wkhlrp--dev04.sandbox.my.site.com/ESWMWBOT1714737671666/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>  
</html>
