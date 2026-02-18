          <div id="countik-widget"></div>
          <script>
            (function() {
              var countikWidget = document.createElement('script');
              countikWidget.src = 'https://countik.com/widget.js';
              countikWidget.async = true;
              countikWidget.onload = function() {
                if (typeof window.initializeCountikWidget === 'function') {
                  window.initializeCountikWidget({
                    container: '#countik-widget',
                    themeColor: '#444444',
                    uniqueId: 'bzhprint3d',
                    language: 'en'
                  });
                }
              };
              var firstScript = document.getElementsByTagName('script')[0];
              firstScript.parentNode.insertBefore(countikWidget, firstScript);
            })();
          </script>
          <a href="https://countik.com/user/bzhprint3d" target="_blank" class="pow-countik" style="font-size:11px;color:#333;display:block;padding:4px 3px;text-decoration:none;">Powered by Countik™</a>
        
