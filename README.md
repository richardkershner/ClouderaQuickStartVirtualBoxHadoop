# ClouderaQuickStartVirtualBoxHadoop
Tutorial on setting up Cloudera (hadoop) single node on Virtual Box

##Virtual Box, Cloudera quick start notes
> Virtual Box allows running a different operating system, client, on a host computer. In this example a Windows 10 home edition has the Virtual Box setup with the disc image.  The disc image is linux Centos with Cloudera, one of the HDFS options, on it. On my Virtual Box I also have Horton's Sandbox which I like because it defaults to letting you access it through your PCs web browser, a more common appearance of real life use.
> http://hortonworks.com/products/sandbox/#downloads
> Select Hortonworks Sandbox on a VM and then the DOWNLOAD FOR VIRTUALBOX
> Also note I have Ubuntu installed on Virtual Box, with hadoop single node... but that is a lengthy process and would need it's own set of instructions.
> In short, this creates a single node for testing and learning HDFS (Hadoop File System) on which is accessable from a PC. 
> 
> Both downloads can be found from their respective sites, FREE. 
  * http://www.cloudera.com/downloads.html    -->  select Quickstarts
    * For the platform Select Virtual Box
    * Before Cloudera finalized their build you had to click the pull down and select an older version.
  * http://www.oracle.com/technetwork/server-storage/virtualbox/downloads/index.html
> 
  * **Note in Virtual Box.**
    * Make sure to use FILE and from the pull down, IMPORT to bring the Cloudera disk image.
      * Using add button will cause errors.
    * When starting up Cloudera in Virtual Box(VB), it will go through a setup screen.  Once the initial setup is done, click the esc button on the keyboard to load the actual linux cloudera.  (Hope that saves somebody the time of looking it up!)
    * In Virtual Box, under Devices, set both shared clipboard and Drag and drop to bidirectional.
       * The Drag and Drop is great for transfering files into VB but requires extra settings to work the other way.
 > 
  *  **Note in Cloudera on the VB**
    * Terminal window easy access icon at the top of the window.
    * HUE and File manager are the main two things used in the web browser.
       * Maximize the window to see File Manager under the HUE as it is way to the right.
    * Updating the linux system in the VB was necessary for one of the problems.  This also caused changes in the windows so the auto sizing doesn't work as good, along with other changes.  This means extra scrolling when viewing different things in the VB.
