<h1>Read and write to a newly created data file</h1>   

<p>  to read and write data other char and String the steps to do this </p>   

<p>1- create an empty file stream  ( private const string FILE_NAME = "AnyName";)</p>

<p>(FileStream fs = new FileStream(FILE_NAME, FileMode.CreateNew))</p>

<p>2-write data to it (BinaryWriter w = new BinaryWriter(fs);)</p>

<p>3-read data from it (BinaryReader r = new BinaryReader(fs))</p>

<p>Write text to a file</p>
<p>stremwrite contains methods to write to a file synchronously (write and writelinrLinks to an external site.) or asynchronously (writeasync and writelineasync).</p>

<p>steps:</p>

<p>1-create a variable (String)</p>

<p>2-create a path</p>

<p>3-wite in the file </p>

<p>StreamWriter outputFile = new StreamWriter(Path.Combine(docPath, "WriteLines.txt" </p>

<p>outputFile.WriteLine(line)</p>

<p>file provides static methods to write text to a file such as writeallline  and writealltext, or to append text to a file such as appendallline  appendalltext, and appendtext.</p>

<p>steps:</p>

<p>1-write the path and save it in a variable</p>

<p>2-append the test</p>

<p>using (StreamWriter outputFile = new StreamWriter(Path.Combine(docPath, "WriteLines.txt"), true)) { outputFile.WriteLine("Fourth Line"); }</p>

<p>path is for strings that have file or directory path information. It contains the combain method and in </p>

<p>steps:</p>

<p>1- create a string with a line of text.</p>

<p>string text = "First line" + Environment.NewLine;</p>

<p>2-path</p>

<p>3-Write the text to a new file named</p>

<p>4-Append new lines of text to the file</p>

<p>File and Stream I/O</p>
<p>refers to the transfer of data either to or from a storage medium enable reading and writing, both synchronously and asynchronously, on data streams and files there are several kinds of streams other than file streams, such as network, memory, and pipe streams.</p>

<p>commonly used file and directory classes</p>

<p>{ file => silestrem , fileinfo=>filestrem directory directoeyinfo path }</p>

<p>strem </p>  

<p>abstract class upports reading and writing bytes All classes that represent streams inherit from the strem class .the strem has three operation write read and seeking </p>
   