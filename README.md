# QT6SSTV
QT6 QSSTV - migration of the QSSTV code to QT6 <p>

<b>!! For more info cleaning the software see the Wiki tab !!</b><p>

The QSSTV repro from ON4QZ is used as base for this ' QT 6 update' version.<br>
So the main copyrights are from ON4QZ<br>
This repro is to give a fresh start in QT6 of the great QSSTV programm who was written based on QT5.<p>

The intention of this repro is to addon more functions on the QSSTV version 9.5.11.<br>
The first step is made - compile the code in QT6 and clean the code as most possible<p>

NOTE !!<br>

Their is an documents folder inside the 'src' folder - this folder is in the *.pro file added.<br>
Changes will be made later, also the HTML files to bring the documents online.<p>

The folder 'manual_html' is the original html (webpages) manual of vs. 9.5 of QSSTV - copyrights of ON4QZ<p>
The next steps are the needed software packages inside your OS ( Linux Mint / Debian )<p>

sudo apt-get install doxygen gmake6 libxcb*-dev libxcb-xinerama0 libxkbcommon-x11-0 <br>
sudo apt-get install libxkbcommon0 libxcb-xv0-dev<br>
sudo apt-get install libv4l-dev libopenjp2-dev libpulse-dev libasound2-dev libhamlib++-dev hamlib-dev<br>
sudo apt-get install libfftw3-dev  <p>

After installing the full QT6 offline package (use NOT the latest QT creator version 6.5 ) Version 6.4.2 at<br>
    the install selection .. then follow the last instruction:<br>
I mean:<p>

    export export PATH=/opt/Qt/6.x.x/gcc_64/bin/:$PATH => 6.x.x is for example 6.4.2
    ln -s /opt/Qt/6.x.x/gcc_64/bin/qmake /usr/bin/qmake

When now testing the qmake --version .. you seen that it is going to qt 6<p>

CQ - CQ to all <b>Hamradio developers</b> - if you feel yourself confortable working with C++ and QT 6<br>
Please try this code, and help us to make it more 'up 2 date' with the new raptorQ modulation forms.<br>





 
