<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>HornetQ FastPack</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>HornetQ FastPack</h1>
    <div class="section-2"  id="78676111_HornetQFastPack-Overview"  >
        <h2>Overview</h2>
    <p>
            <img src="images_community/download/attachments/78676111/icon.png" alt="images_community/download/attachments/78676111/icon.png" class="confluence-embedded-image image-left" />
            </p>
    <p>
    </p>
    <p>
The HornetQ FastPack provides <strong class=" ">sensors</strong> in a template <strong class=" ">system profile</strong> and a <strong class=" ">dashboard</strong> for the HornetQ messaging system.<br/>Please also see the article on <a href="https://community/display/LEARN/How+To+Manage+HornetQ+based+Applications">How To Manage HornetQ based Applications</a>.    </p>
    </div>
    <div class="section-2"  id="78676111_HornetQFastPack-FastPackDetails"  >
        <h2>FastPack Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">HornetQ FastPack</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1.0    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
4.x    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Derek Abing    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community+Supported">Not Supported</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
FastPack Contents    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_78839835_1_HornetQ_FastPack.dtp">FastPack Package (System Profile with sensors and Dashboards)</a>    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="78676111_HornetQFastPack-HornetQDashboard"  >
        <h2>HornetQ Dashboard</h2>
    <p>
            <img src="images_community/download/attachments/78676111/HornetQ_Dashboard.JPG" alt="images_community/download/attachments/78676111/HornetQ_Dashboard.JPG" class="" />
            </p>
    <p>
This dashboard provides helps identifying performance problems in the overall message processing infrastructure of HornetQ.    </p>
<ul class=" "><li class=" ">    <p>
<strong class=" ">Consumer Count</strong>: indicates how many consumers are currently running.    </p>
</li><li class=" ">    <p>
<strong class=" ">Message Count</strong>: indicates that messages aren&rsquo;t being processed in a timely manner.    </p>
</li><li class=" ">    <p>
<strong class=" ">Number of Pages</strong>: indicates that the queues memory quota is filled.    </p>
</li></ul>    <p>
The dashboard is collecting the data for these measures on the DLQ and ExpiryQueue Queues. These queues are generally used as buckets to hold messages that have expired or cannot be delivered.    </p>
    </div>
    <div class="section-2"  id="78676111_HornetQFastPack-Installation"  >
        <h2>Installation</h2>
<ol class=" "><li class=" ">    <p>
Import the <a href="attachments_78839835_1_HornetQ_FastPack.dtp">FastPack</a> into your dynaTrace Server using your dynaTrace client.    </p>
</li><li class=" ">    <p>
As this FastPack doesn't contain a plugin, it will NOT show up in the plugins overview of your dynaTrace Server. After a dialog box informing you about the successful installation, you will see a new system profile as well as a new dashboard, both called &quot;HornetQ&quot;.    </p>
</li></ol>    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
