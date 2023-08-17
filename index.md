<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
    <title>MIAW</title>
</head>
<body>
    	<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D0k0000005KxQ',
				'Github_MIAW',
				'https://downstream--osdbsd.sandbox.my.site.com/ESWGithubMIAW1692274171713',
				{
					scrt2URL: 'https://downstream--osdbsd.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://downstream--osdbsd.sandbox.my.site.com/ESWGithubMIAW1692274171713/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
