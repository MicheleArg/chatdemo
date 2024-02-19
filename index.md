<html>
	<head>
		<meta name="referrer" content="no-referrer" />
	</head>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'it'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D3N000000Hajb',
				'Areti_Web_Chat',
				'https://aretispa--qualitya.sandbox.my.site.com/ESWAretiWebChat1707821677243',
				{
					scrt2URL: 'https://aretispa--qualitya.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://aretispa--qualitya.sandbox.my.site.com/ESWAretiWebChat1707821677243/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>
