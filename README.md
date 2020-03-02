# AnalyticsOnly

Single JS file integration for Mogi Video Analytics


Add following script in your file after “videojs”. Like :

<script src="https://analyticsonly.mogiio.com/fingerprint.js"> </script>


Call below function and pass the parameter. 

Fingerprint2.analytics(VideoElementId, AppId, UserId);

Required params : 

    VideoElementId : Id of video element in html file. 

    AppId : Id of video app provided by Mogi I/O.

Optional params : 

    UserId : Registered Id of User. 


Now you can see analytics in Mogi I/O Tech Portal.
