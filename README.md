<html>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'ja'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D0T0000000R19',
				'miaw',
				'https://d5i00000duzwneat--dev02.sandbox.my.site.com/ESWmiaw1695091989069',
				{
					scrt2URL: 'https://d5i00000duzwneat--dev02.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://d5i00000duzwneat--dev02.sandbox.my.site.com/ESWmiaw1695091989069/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</html>
