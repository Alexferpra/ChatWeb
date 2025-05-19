<html>
  <body>
    <script type='text/javascript'>
    	function initEmbeddedMessaging() {
    		try {
    			embeddedservice_bootstrap.settings.language = 'es'; // For example, enter 'en' or 'en-US'
          embeddedservice_bootstrap.prechatAPI.setVisiblePrechatFields({"Email" : {"value": "alejandro.fdezpradel@inetum.com", "isEditableByEndUser": false }});
    			embeddedservice_bootstrap.init(
    				'00D5E00000091lt',
    				'SAV_esd_SaviaChatWeb',
    				'https://mapfresaluddigital--dev.sandbox.my.site.com/ESWSAVesdSaviaChatWeb1745482924601',
    				{
    					scrt2URL: 'https://mapfresaluddigital--dev.sandbox.my.salesforce-scrt.com'
    				}
    			);
    		} catch (err) {
    			console.error('Error loading Embedded Messaging: ', err);
    		}
    	};
    </script>
    <script type='text/javascript' src='https://mapfresaluddigital--dev.sandbox.my.site.com/ESWSAVesdSaviaChatWeb1745482924601/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>	
  </body>
</html>
