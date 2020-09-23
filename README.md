<div align="center">

## PipeBoost Internet Information Server \(IIS\) Content Compression Product


</div>

### Description

Pipebost is a content compression product that dynamically compresses content served out by your IIS server before it gets to the browser. This dramatically reduces the time it takes the document to load in the user's browser as well as cuts down on bandwidth usage. For example, PipeBoost has reduced the bandwidth usage on PlanetSourceCode.com by a whopping 27% --which is basically an entire T1! And the .asp pages load much quicker...about 50% faster than before. The slower your connection the more you notice PipeBoost.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ian Ippolito \(vWorker\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ian-ippolito-vworker.md)
**Level**          |Beginner
**User Rating**    |3.5 (38 globes from 11 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Server Side](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/server-side__4-31.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ian-ippolito-vworker-pipeboost-internet-information-server-iis-content-compression-product__4-7164/archive/master.zip)





### Source Code

<p><span lang="en-us"><b><font face="Verdana">How does it work</font></b></span><font face="Verdana"><b><span lang="en-us">?</span></b></font></p>
<p><font face="Verdana" size="2"><span lang="en-us">    How does
it work?  If you think about it the .htm, .asp, etc. files being served by
IIS are not very efficient...they are basically bulky text files.  If you
could compress them before sending them out, your download times would be
greatly shortened. </span></font></p>
<p><font face="Verdana" size="2"><span lang="en-us">   I didn't know
this before, but the HTTP 1.1 standard actually already includes support for
this sort of compression.  This standard is supported in 95% of
browsers...IE4.0+, Netscape 4.0+ and Opera 4.0+). However, you do need the right
software on your internet server to recognize the browser and serve it out
compressed content...and most servers don't have this.</span></font></p>
<p><font face="Verdana" size="2"><span lang="en-us">    Microsoft
included such a feature in IIS...but if you've used it, you know that it's a
little buggy and it only works on static HTM pages...not your dynamic ASP pages.</span></font></p>
<p><font face="Verdana" size="2"><span lang="en-us">    That's
where <a href="http://www.pipeboost.com/psc.asp">PipeBoost</a> comes into play.  It can compress content on the fly and
serve it to the browser, which un-compresses it and displays it.  It is so
simple to implement...you just run a short 3 minute install program and its
ready to go...no configuration required on either the server or the browser (of
course if you want to get fancy you can tweak the server GUI for hours...but for
most installations the default install will be more than adequate).</span></font></p>
<p><font face="Verdana"><b><span lang="en-us">Test Results</span></b></font></p>
<p><font face="Verdana"><span lang="en-us"><b>    </b>
<font size="2">Before rolling out PipeBoost, I tested it in the lab.  I
downloaded the trial version and installed it on a server here in Tampa,
Florida.  Then I put a test 9.12 Mb Excel Spreadsheet in a test directory
and downloaded it from a browser located in Boston, Mass.  (this was done
via terminal server) and measured the results.</font></span></font></p>
<p><font face="Verdana" size="2"><span lang="en-us">    The
improvement was eye-popping.</span></font></p>
<center>
<table border="0" cellpadding="2" style="border-collapse: collapse" bordercolor="#111111" width="80%" id="AutoNumber1">
 <tr>
 <td width="33%" bgcolor="#000000"> </td>
 <td width="4%" bgcolor="#000000"> </td>
 <td width="63%" bgcolor="#000000">
 <font color="#FFFFFF" face="Verdana" size="1"><b><span lang="en-us">Time to
 download</span></b></font></td>
 </tr>
 <tr>
 <td width="33%"><span lang="en-us"><font size="2" face="Verdana">No
 compression</font></span></td>
 <td width="4%"> </td>
 <td width="63%"><span lang="en-us"><font size="2" face="Verdana">1 minute 2
 seconds</font></span></td>
 </tr>
 <tr>
 <td width="33%"><span lang="en-us"><font size="2" face="Verdana">PipeBoost
 compression</font></span></td>
 <td width="4%"> </td>
 <td width="63%"><span lang="en-us"><font size="2" face="Verdana">23 seconds</font></span></td>
 </tr>
 <tr>
 <td width="33%"> </td>
 <td width="4%"> </td>
 <td width="63%"> </td>
 </tr>
 <tr>
 <td width="33%"><b><font size="2" face="Verdana">Difference:</font></b></td>
 <td width="4%"> </td>
 <td width="63%"><b><font size="2" face="Verdana">3.7 x speed increase</font></b></td>
 </tr>
</table>
<p><font size="2" face="Verdana">    After rolling it into
production, I immediately saw a 27% decrease in bandwidth usage...or about an
entire T1 worth of data.  Planet Source Code actually has alot more
compressed .zip files than most sites do (which of course can't be further
compressed by PipeBoost), so most sites should see an even <b>larger</b> decrease in
bandwidth.</font></p>
<p align="left"><b><font face="Verdana">Trying it on your own</font></b></p>
<center>
<p><font face="Verdana" size="2">   
<a href="http://www.pipeboost.com/psc.asp">PipeBoost</a> has a great tool
on their web site that lets you test their product on your own web site, without
having to install it...to get an idea of how much it can compress your content
and save you.  Just go to PipeBoost and click on "Request Report" and then
type in your URL.  The Planet Source Code home page showed that it could be
compressed 73%!</font></p>
<p align="left"><b><font face="Verdana">My Conclusion</font></b></p>
<center>
<p><font face="Verdana" size="2">    This is one of the few 'must
have' products for IIS.  I your website does anything more than trivial
traffic, you should seriously
consider this program.  To download this program , go to
<a href="http://www.pipeboost.com/psc.asp">PipeBoost</a> and click on
'Downloads'.</font></p>

