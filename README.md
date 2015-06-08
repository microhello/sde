test<p>Structured Data Extractor (SDE) is an implementation of <a href="http://www.cs.uic.edu/~yzhai/paper/www05_depta.pdf">DEPTA</a> (Data Extraction based on Partial Tree Alignment), a method to extract data from web pages (HTML documents). DEPTA was invented by <a href="http://www.cs.uic.edu/~yzhai/">Yanhong Zhai</a> and <a href="http://www.cs.uic.edu/~liub/">Bing Liu</a> from University of Illinois at Chicago and was published in their paper: "Structured Data Extraction from the Web based on Partial Tree Alignment" (<em>IEEE Transactions on Knowledge and Data Engineering</em>, 2006). Given a web page, SDE will detect <em>data records</em> contained in the web page and extract them into table structure (rows and columns). You can download the application from this link: <a href="http://seagatesoft.com/download/sde.zip">Download Structured Data Extractor</a>.</p>
<h3>Usage</h3>
<p>
<ol>
<li>Extract sde.zip.</li>
<li>Make sure that Java Runtime Environment (version 5 or higher) already installed on your computer.</li>
<li>Open <em>command prompt</em> (Windows) or <em>shell</em> (UNIX).</li>
<li>Go to the directory where you extract sde.zip.</li>
<li>Run this command: <code>java -jar sde-runnable.jar URI_input path_to_output_file</code></li>
<li>You can pass <em>URI_input</em> parameter refering to a local file or remote file, as long as it is a valid URI. URI refering to a local file must be preceded by "file:///". For example in Windows environment: "file:///D:/Development/Proyek/structured_data_extractor/bin/input/input.html" or in UNIX environment: "file:///home/seagate/input/input.html".</li>
<li>The path to output file parameter is formatted as a valid path in the host operating system like "D:\Data\output.html" (Windows) or "/home/seagate/output/output.html" (UNIX).</li>
<li>Extracted data can be viewed in the output file. The output file is a HTML document and the extracted data is presented in HTML tables.</li>
</ol>
</p>
<h3>Source Code</h3>
<p>SDE source code is available at <a href="https://github.com/seagatesoft/sde">GitHub</a>.</p>
<h3>Dependencies</h3>
<p>SDE was developed using these libraries:
<ul>
<li><a href="http://nekohtml.sourceforge.net/">Neko HTML Parser</a> by Andy Clark and Marc Guillemot. Licensed under Apache License Version 2.0.</li>
<li><a href="http://xerces.apache.org/">Xerces</a> by The Apache Software Foundation. Licensed under Apache License Version 2.0.</li>
</ul>
</p>
<h3>License</h3>
<p>SDE is licensed under the MIT license.</p>
<h3>Author</h3>
<p>Sigit Dewanto, sigitdewanto11[at]yahoo[dot]co[dot]uk, 2009.</p>