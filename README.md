<!DOCTYPE html>
<html class="no-js" lang="en">
  <head>
  </head>
  <body>
    <div class="wrapAll clearfix">
      <div class="mainsection"><br>
        <div class="article">
          <h1> Windows Subsystem for Android (WSA) and
            SDR.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          </h1>
          <br>
          A Windows feature present in Windows 11.<br>
          <br>
          <img src="img/desktop.jpg" alt="" width="686" height="433"><br>
          <br>
          Windows Subsystem for Android - WSA.<br>
          <br>
          Windows Subsystem for Android (WSA) enables your Windows 11
          device to run Android apps in Windows just like any other
          native Windows based application.<br>
          The apps are delivered to Windows 11 via the Amazon App Store,
          but it is possible to sideload virtually any Android .APK file
          so you can run many apps that are not currently in the store.<br>
          <br>
          WSA has different system requirements than Windows 11, so
          simply having 11 installed is not enough. <br>
          WSA requires at least 8 GB of RAM, a solid-state drive (SSD),
          and a supported processor (Intel® Core™ i3 8th Generation, AMD
          Ryzen™ 3000, Qualcomm® Snapdragon™ 8c, or above).<br>
          <br>
          <p style="line-height: inherit; margin: 0px 0px 20px;
            font-family: sans-serif; font-style: normal;
            font-variant-ligatures: normal; font-variant-caps: normal;
            letter-spacing: normal; orphans: 2; text-align: start;
            text-indent: 0px; text-transform: none; white-space: normal;
            widows: 2; word-spacing: 0px; -webkit-text-stroke-width:
            0px; background: 0px 0px rgb(255, 255, 255);
            text-decoration-style: initial; text-decoration-color:
            initial; padding: 0px; border: 0px; outline: 0px; font-size:
            15px; vertical-align: baseline; color: rgb(68, 68, 68);
            font-weight: 300; user-select: auto !important;"> </p>
          <div class="contentsPanel">
            <div class="contentsHeader">Contents: </div>
            <ul>
              <li> <span></span>Overview
                <ul>
                  <li><span>1.1&nbsp; <a href="#Enable_WSL_">Enable WSA
                        Subsytem</a><br>
                    </span></li>
                  <li><span>1.2&nbsp; <a href="#Install_Distro_">Install
                        WSA</a><br>
                    </span></li>
                  <li><span>1.3&nbsp; <a href="#APK_Installers_">APK
                        Installers</a><br>
                    </span></li>
                  <li><span>1.4&nbsp; <a href="#Install_SDR_">Install
                        RTL_TCP</a><br>
                    </span></li>
                  <li><span>1.5&nbsp; <a href="#MagicSDR_">MagicSDR</a></span><br>
                  </li>
                  <li><span>1.6&nbsp; <a href="#SDRTouch_">SDRTouch</a><br>
                    </span></li>
                  <li><span>1.7&nbsp; <a href="#Rf_Analyzer_">RF
                        Analyzer</a><br>
                    </span></li>
                  <li><span>1.8&nbsp; <a href="#FM_Radio_">FM Radio</a><br>
                    </span></li>
                  <li><span>1.9&nbsp; <a href="#Other_Apps_">Other Apps</a><a
                        href="#Gpredict__WxToImg"><br>
                      </a></span></li>
                  <li><span>2.0&nbsp; <a
                        href="#Backup__Restore_WSA_Images_">Backup/Restore
                        Images</a><br>
                    </span></li>
                   <li><span>2.0&nbsp; <a
                        href="#Usefull_Links_">Usefull
                            Links</a><br>
                    </span></li>
                </ul>
              </li>
            </ul>
          </div>
          <h2>Enable WSA Subsytem<br>
          </h2>
          <br>
          <b>Enable Windows Subsystem for Android:</b><br>
          <br>
          You may need to enable virtualization for your PC’s BIOS,
          check mainboard manual.<br>
          <br>
          Enable the Virtual Machine Platform <br>
          <br>
          In Control Panel, under Programs =&gt; Windows Features, check
          mark<b>:<br>
            <br>
          </b>Hyper-V and subcomponents (Hyper-V Management Tools and
          Platform),<br>
          Virtual Machine Platform, <br>
          Windows Hypervision Platform.<br>
          <br>
          For this action to take effect, you have to <b>restart the
            computer.</b><br>
          <br>
          <img src="img/hyperv.jpg" alt="" width="697" height="632"><br>
          <h2>Install WSA<br>
          </h2>
          <br>
          The Android compatibility layer of Windows 11, commonly known
          as Windows Subsystem for Android (WSA), comes without the
          Google Play Store or any kind of Google apps. <br>
          Instead, you get the Amazon Appstore as the built-in solution
          for downloading third-party apps. <br>
          <br>
          1: Install Amazon Appstore from the Store (US only).<br>
          <br>
          2: Use WSA-Toolbox manual for a <a
            href="https://github.com/voletro/wsa-toolbox/blob/main/installation.md">Installation
            with MsiBundle andPowershell</a>.<br>
          <br>
          3: Use MagiskOnWSA from LSPosed for a <a
            href="https://github.com/LSPosed/MagiskOnWSA">Installation
            with Root,Magisk and Google Apps</a>.<br>
          <br>
          <img src="img/settings.jpg" alt="" width="978" height="527"><br>
          <br>
          <img src="img/Gfx.jpg" alt="" width="998" height="550"><br>
          <h2><a name="APK_Installers_"></a>APK Installers<br>
          </h2>
          <p> </p>
          <span></span><g-emoji class="g-emoji" alias="moneybag"
fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4b0.png"
            style="box-sizing: border-box; font-family: &quot;Apple
            Color Emoji&quot;, &quot;Segoe UI&quot;, &quot;Segoe UI
            Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 1.2em;
            font-weight: 400; line-height: 20px; vertical-align: middle;
            font-style: normal !important;"></g-emoji><g-emoji
            class="g-emoji" alias="moneybag"
fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4b0.png"
            style="box-sizing: border-box; font-family: &quot;Apple
            Color Emoji&quot;, &quot;Segoe UI&quot;, &quot;Segoe UI
            Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 1.2em;
            font-weight: 400; line-height: 20px; vertical-align: middle;
            font-style: normal !important;"></g-emoji> <br>
          It is possible to manually sideload apps on WSA,but there is
          no simple way to manage all the installed apps on the Android
          subsystem — unless you install a launcher, or go one step
          further and enable the Play Store.<br>
          &nbsp;<br>
          WSA PacMan is a package manager utility for Windows Subsystem
          for Android. <br>
          Created by XDA Senior Member alesimula, the open-source tool
          aims to streamline the app sideloading job by providing an
          easy-to-use GUI installer for APK files. <br>
          It also displays the full package name of the APK, its version
          number, the permissions, and the icon — almost like the
          standard package manager app does on an actual Android device.<br>
          <br>
          <img src="img/pacman.jpg" alt="" width="582" height="435"><br>
          <br>
          When it comes to app management, WSA PacMan provides a button
          to open the Settings app from the Android subsystem, so that
          you can change the underlying parameters as necessary. <br>
          There is another button that directly opens the “Manage
          Applications” page, from which you can uninstall or disable
          installed applications and grant or revoke permissions. <br>
          Furthermore, the tool’s installation wizard offers you the
          ability to create a shortcut of the app that you are
          installing on your Windows desktop.<br>
          <br>
          <a href="https://github.com/alesimula/wsa_pacman/releases">Download
            Pacman</a><br>
          <br>
          WSA Toolbox this project includes tools to install and use the
          Windows Subsystem For Android™ platform on Windows 11. <br>
          These tools include:<br>
          <br>
          <img src="img/WSA_Toolbox.jpg" alt="" width="307" height="349"><br>
          <br>
          Installation of any APK file in one click.<br>
          Access to the ADB Shell.<br>
          Installation of Windows Subsystem For Android™ in unsupported
          regions,Aurora Store as an alternative to the Google Play
          Store.<br>
          <br>
          <img
src="img/start.jpg"
            alt="" width="662" height="421"><br>
          <br>
          Installation of a simple app launcher for easy access to other
          apps.<br>
          <br>
          <img src="img/start2.jpg" alt="" width="662" height="505"><br>
          <br>
          <a href="https://github.com/voletro/wsa-toolbox">Download WSA
            Toolbox</a><br>
          <h2>Install RTL_TCP<br>
          </h2>
          <br>
          Install RTL-TCP for windows.<br>
          <br>
          <a href="https://ftp.osmocom.org/binaries/windows/rtl-sdr/"
            target="_blank">Download Windows rtl-tools package</a>,
          extract within a folder.<br>
          <br>
          Now you can use rtl_tcp<br>
          <br>
          Change ip adres to 127.0.0.1 or local ip adres.<br>
          rtl_tcp -a &lt;local ip&gt;<br>
          <br>
          For other SDR Devices this is also possible:<br>
          <br>
          SDR-Play TCP<br>
          <br>
          <a
            href="https://www.sdrplay.com/software/SDRplay_RSP_TCP_1.1_Windows.zip"
            target="_blank">https://www.sdrplay.com/software/SDRplay_RSP_TCP_1.1_Windows.zip</a><br>
          <br>
          Change ip adres to 127.0.0.1 or local ip adres.<br>
          rsp_tcp -a &lt;local ip&gt;<br>
          <br>
          <h2><a name="MagicSDR_"></a>MagicSDR<br>
          </h2>
          <br>
          <img src="img/MagicSDR2.jpg" alt="" width="318" height="504"><br>
          <br>
          Press the 3 dots right above to configure rtl tcp.<br>
          <br>
          <img src="img/MagicSDR.jpg" alt="" width="319" height="508"><br>
          <br>
          Change ip adres to 127.0.0.1 or local, go back and press play.<br>
          Make sure a rtl_tcp server is running! <br>
          <br>
          <img src="img/MagicSDR3.jpg" alt="" width="317" height="503"><br>
          <br>
          In some settings you can reduce the CPU load further by
          reducing the window size, sample rate, FFT rate and FFT size.<br>
          <h2><a name="SDRTouch_"></a>SDRTouch<br>
          </h2>
          <br>
          Configure rtl tcp by pressing Open.<br>
          <br>
          <img src="img/SDRTouch2.jpg" alt="" width="617" height="377"><br>
          <br>
          <img src="img/SDRTouch3.jpg" alt="" width="620" height="380"><br>
          <br>
          Change ip adres to 127.0.0.1 or local, go back and press play.<br>
          Make sure a rtl_tcp server is running! <br>
          <br>
          <img src="img/SDRTouch4.jpg" alt="" width="623" height="381"><br>
          <br>
          Gain can be set to manual or auto.<br>
          In some settings you can reduce the CPU load further by
          reducing the window size, sample rate, FFT rate and FFT size.<br>
          <br>
          <img src="img/SDRTouch.jpg" alt="" width="624" height="382"><br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br>
          Press the Power above button to play, click spectrum to show.<br>
          <br>
          <img src="img/SDRTouch_RDS.jpg" alt="" width="627"
            height="384"><br>
          <h2><a name="Rf_Analyzer_"></a>Rf Analyzer<br>
          </h2>
          <br>
          Press the 3 dots right above to configure rtl tcp.<br>
          <br>
          <img src="img/RF_Analyzer.jpg" alt="" width="638" height="390"><br>
          <br>
          <img src="img/RF_Analyzer2.jpg" alt="" width="638"
            height="390"><br>
          <br>
          Set Source Type to rtl-SDR.<br>
          Click Source Settings to configure rtl tcp.<br>
          <br>
          <img src="img/SDRTouch3.jpg" alt="" width="646" height="395"><br>
          <br>
          Change ip adres to 127.0.0.1 or local, go back and press play.<br>
          Make sure a rtl_tcp server is running! <br>
          <br>
          <img src="img/RF_Analyzer4.jpg" alt="" width="646"
            height="395"><br>
          <br>
          In some settings you can reduce the CPU load further by
          reducing the window size, sample rate, FFT rate and FFT size.<br>
          <h2><a name="FM_Radio_"></a>FM Radio<br>
          </h2>
          <img src="img/FM-Radio.jpg" alt="" width="643" height="398"><br>
          <br>
          Press the 3 dots right above to configure rtl tcp.<br>
          Change ip adres to 127.0.0.1 or local, go back and press play.<br>
          <br>
          Make sure a rtl_tcp server is running! <br>
          <h2><a name="Other_Apps_"></a>Other Apps<br>
          </h2>
          <br>
          <img src="img/AMsat.jpg" alt="" width="294" height="524"><br>
          <br>
          AmsatDroid<br>
          <br>
          <img src="img/aprsdroid.jpg" alt="" width="540" height="380"><br>
          <p>APRSDroid<br>
          </p>
          <img src="img/Filemanager.jpg" alt="" width="533" height="330"><br>
          Filemanager<br>
          <p> <br>
          </p>
          <img src="img/Heavens_Above.jpg" alt="" width="770"
            height="544"><br>
          <br>
          <p>Heavens Above<br>
            <br>
          </p>
          <p><img src="img/iss.jpg" alt="" width="776" height="482"></p>
          <p><br>
            ISS Live Now<br>
          </p>
          <p><br>
            <img src="img/Terminal.jpg" alt="" width="721" height="441"><br>
          </p>
          <p>Terminal<br>
          </p>
          <h2><a name="Backup__Restore_WSA_Images_"></a>Backup / Restore
            WSA Images<br>
          </h2>
          <p> </p>
          <b> </b>
          <p><br>
            In case of local cache corruption, Apps and userdata can be
            backup/restored.<br>
          </p>
          <p><img src="img/vhdx.jpg" alt="" width="936" height="534"></p>
          <p>If local cache corruption us really bad Uninstall WSA<br>
          </p>
          <img src="img/uninstall.jpg" alt="" width="983" height="664">
          <h2>Usefull Links<br>
          </h2>
          <p> </p>
          <br>
          https://www.reddit.com/r/WSA/<br>
          <br>
          https://docs.microsoft.com/en-us/windows/android/wsa/<br>
          <br>
https://www.xda-developers.com/tag/windows-subsystem-for-android/<br>
          <br>
https://github.com/riverar/wsa-app-compatibility/wiki/Application-Compatibility<br>
          <br>
        </div>
  </body>
</html>
