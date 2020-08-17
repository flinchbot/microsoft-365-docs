<!--THIS FILE IS AUTOMATICALLY GENERATED. MANUAL CHANGES WILL BE OVERWRITTEN.-->
<!--Please contact the Office 365 Endpoints team with any questions.-->
<!--USGovGCCHigh endpoints version 2020072800-->
<!--File generated 2020-08-08 08:00:09.9418-->

## Exchange Online

ID | Category | ER | Addresses | Ports
-- | -------------------- | --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------
1 | Optimize<BR>Required | Yes | `outlook.office365.us`<BR>`40.66.16.0/21, 131.253.83.0/26, 131.253.84.64/26, 131.253.84.192/26, 131.253.86.0/24, 131.253.87.144/28, 131.253.87.208/28, 131.253.87.240/28, 131.253.88.0/28, 131.253.88.32/28, 131.253.88.48/28, 131.253.88.96/28, 131.253.88.128/28, 131.253.88.144/28, 131.253.88.160/28, 131.253.88.192/28, 131.253.88.240/28, 2001:489a:2200:28::/62, 2001:489a:2200:3c::/62, 2001:489a:2200:44::/62, 2001:489a:2200:400::/56` | **TCP:** 443, 80
4 | Default<BR>Required | Yes | `attachments.office365-net.us, autodiscover.<tenant>.mail.onmicrosoft.com, autodiscover.<tenant>.mail.onmicrosoft.us, autodiscover.<tenant>.onmicrosoft.com, autodiscover.<tenant>.onmicrosoft.us, autodiscover-s.office365.us` | **TCP:** 443, 80
5 | Default<BR>Required | Yes | `outlook.office365.us` | **TCP:** 143, 25, 587, 993, 995
6 | Allow<BR>Required | Yes | `*.manage.office365.us, *.protection.office365.us, *.scc.office365.us, manage.office365.us, scc.office365.us`<BR>`13.72.179.197/32, 13.72.183.70/32, 23.103.191.0/24, 23.103.199.128/25, 23.103.208.0/22, 52.227.170.14/32, 52.227.170.120/32, 52.227.178.94/32, 52.227.180.138/32, 52.227.182.149/32, 52.238.74.212/32, 2001:489a:2202:4::/62, 2001:489a:2202:c::/62, 2001:489a:2202:2000::/63` | **TCP:** 25, 443

## SharePoint Online and OneDrive for Business

ID | Category | ER | Addresses | Ports
-- | -------------------- | --- | ------------------------------------------------------------------------------------------------------------------------- | ----------------
9 | Optimize<BR>Required | Yes | `*.sharepoint.us`<BR>`20.34.8.0/22, 104.212.50.0/23, 2001:489a:2204:2::/63, 2001:489a:2204:800::/54` | **TCP:** 443, 80
10 | Default<BR>Required | No | `*.wns.windows.com, admin.onedrive.us, g.live.com, odc.officeapps.live.com, officeclient.microsoft.com, oneclient.sfx.ms` | **TCP:** 443, 80
20 | Default<BR>Required | No | `*.svc.ms, az741266.vo.msecnd.net, spoprod-a.akamaihd.net, static.sharepointonline.com, tb.pipe.aria.microsoft.com` | **TCP:** 443, 80

## Skype for Business Online and Microsoft Teams

ID | Category | ER | Addresses | Ports
-- | -------------------- | --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------
7 | Optimize<BR>Required | Yes | `*.gov.teams.microsoft.us, *.infra.gov.skypeforbusiness.us, *.online.gov.skypeforbusiness.us, gov.teams.microsoft.us`<BR>`52.127.88.0/21, 52.238.114.160/32, 52.238.115.146/32, 52.238.117.171/32, 52.238.118.132/32, 52.247.167.192/32, 52.247.169.1/32, 52.247.172.50/32, 52.247.172.103/32, 104.212.44.0/22, 195.134.228.0/22` | **TCP:** 443, 80<BR>**UDP:** 3478, 3479, 3480, 3481
21 | Default<BR>Required | No | `msteamsstatics.blob.core.usgovcloudapi.net, statics.teams.microsoft.com, teamsapuiwebcontent.blob.core.usgovcloudapi.net` | **TCP:** 443

## Microsoft 365 Common and Office Online

ID | Category | ER | Addresses | Ports
-- | ------------------- | --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------
11 | Allow<BR>Required | Yes | `*.gov.online.office365.us`<BR>`52.127.37.0/24, 52.127.82.0/23` | **TCP:** 443
12 | Default<BR>Required | Yes | `*.cdn.office365.us` | **TCP:** 443
13 | Allow<BR>Required | Yes | `*.gov.us.microsoftonline.com, graph.microsoft.us, graph.microsoftazure.us, login.microsoftonline.us`<BR>`20.140.232.0/23, 52.126.194.0/23` | **TCP:** 443
14 | Default<BR>Required | No | `*.msauth.net, *.msauthimages.us, *.msftauth.net, *.msftauthimages.us, clientconfig.microsoftonline-p.net, graph.windows.net, login.microsoftonline.com, login.microsoftonline-p.com, login.windows.net, loginex.microsoftonline.com, login-us.microsoftonline.com, mscrl.microsoft.com, nexus.microsoftonline-p.com, secure.aadcdn.microsoftonline-p.com` | **TCP:** 443
15 | Default<BR>Required | No | `officehome.msocdn.us, prod.msocdn.us` | **TCP:** 443, 80
16 | Allow<BR>Required | Yes | `portal.office365.us, webshell.suite.office365.us, www.office365.us`<BR>`13.72.179.48/32, 52.227.167.206/32, 52.227.170.242/32` | **TCP:** 443, 80
17 | Allow<BR>Required | Yes | `*.osi.office365.us, gcchigh.loki.office365.us, tasks.office365.us`<BR>`52.127.240.0/20, 2001:489a:2206::/48` | **TCP:** 443
18 | Default<BR>Required | No | `activation.sls.microsoft.com, crl.microsoft.com, go.microsoft.com, insertmedia.bing.office.net, ocsa.officeapps.live.com, ocsredir.officeapps.live.com, ocws.officeapps.live.com, office15client.microsoft.com, officecdn.microsoft.com, officecdn.microsoft.com.edgesuite.net, officepreviewredir.microsoft.com, officeredir.microsoft.com, ols.officeapps.live.com, r.office.microsoft.com` | **TCP:** 443, 80
19 | Default<BR>Required | No | `cdn.odc.officeapps.live.com, odc.officeapps.live.com, officeclient.microsoft.com` | **TCP:** 443, 80
23 | Default<BR>Required | No | `*.office365.us` | **TCP:** 443, 80
24 | Default<BR>Required | No | `lpcres.delve.office.com` | **TCP:** 443
25 | Default<BR>Required | No | `*.cdn.office.net` | **TCP:** 443
26 | Allow<BR>Required | Yes | `*.compliance.microsoft.us, *.security.microsoft.us, compliance.microsoft.us, security.microsoft.us`<BR>`13.72.179.197/32, 13.72.183.70/32, 23.103.191.0/24, 23.103.199.128/25, 23.103.208.0/22, 52.227.170.14/32, 52.227.170.120/32, 52.227.178.94/32, 52.227.180.138/32, 52.227.182.149/32, 52.238.74.212/32, 2001:489a:2202:4::/62, 2001:489a:2202:c::/62, 2001:489a:2202:2000::/63` | **TCP:** 443, 80
27 | Allow<BR>Required | Yes | `*.gov.microsoftstream.us`<BR>`20.140.160.0/24, 20.140.162.0/24` | **TCP:** 1935, 1936, 2935, 2936, 443