<!-- Meta Pixel Code -->
<script>
!function(f,b,e,v,n,t,s)
{if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};
if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];
s.parentNode.insertBefore(t,s)}(window, document,'script',
'https://connect.facebook.net/en_US/fbevents.js');
fbq('init', '1411564109272155');
fbq('track', 'PageView');
</script>
<noscript><img height="1" width="1" style="display:none"
src="https://www.facebook.com/tr?id=1411564109272155&ev=PageView&noscript=1"
/></noscript>
<!-- End Meta Pixel Code -->

## Welcome to Conversions API


The Conversions API creates a connection between an advertiser’s marketing data and the Meta systems that optimize ad targeting, decrease cost per action and measure results. In the case of direct integrations, this entails establishing a connection between an advertiser’s server and Meta.

Server events are linked to a Meta Pixel ID and are processed like web events sent via Pixel. This means that web server events are used in measurement, reporting, and optimization in a similar way as browser Pixel events.

For optimal ad performance, we recommend that advertisers implement the Conversions API alongside their Meta Pixel and follow other best practices.


### Recommended Steps


1. Get Started: Choose the integration method that works best for you, see prerequisites for using the API, and understand where to begin.
2. Implement the API and start sending requests: Start making POST requests and learn more about dropped events, batch requests, and event transaction time.
3. Verify your setup: Confirm that we have received your events and that events are deduplicated and matched correctly.
