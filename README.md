# ASP Visual Basic Concepts
 VB.Net and ASP.Net

 
 Namespace
 https://www.c-sharpcorner.com/UploadFile/82f282/what-is-namespace-in-VB-Net/
 
 http://www.dotnetbull.com/2011/11/what-is-namespace-in-net.html
 
 NameSpace is the Logical group of types or we can say namespace is a container (e.g Class, Structures, Interfaces, Enumerations, Delegates etc.), example System.IO logically groups input output related features , System.Data.SqlClient is the logical group of ado.net Connectivity with Sql server related features. In Object Oriented world, many times it is possible that programmers will use the same class name, Qualifying NameSpace with class name can avoid this collision.
 
 Software projects consist of several pieces of code such as classes, declarations, procedures and functions etc., known as the component or identifiers of the software project. In large projects the number of these components can be very large. These components can be grouped into smaller subcategories. This logical grouping construct is known as a "Namespace" or we can say that the group of code having a specific name is a "Namespace".
 
 https://www.tutorialspoint.com/vb.net/vb.net_exception_handling.htm

 Why Throw our own Exceptions?
 
 Slide 15
 
 We throw our own Exceptions, when 
 
 we want to handle our own Exceptions, that is not defined/found in existing Exceptions
 we want to give a proper message to the user when the exception occurs

 https://docs.microsoft.com/en-us/dotnet/visual-basic/programming-guide/language-features/events/
 https://www.tutorialspoint.com/vb.net/vb.net_event_handling.htm

 https://www.red-gate.com/simple-talk/dotnet/net-framework/custom-events-in-vb-net-2005/


 System 
 https://docs.microsoft.com/en-us/dotnet/api/system?view=netframework-2.0

 The System namespace contains fundamental classes and base classes that define commonly-used value and reference data types, events and event handlers, interfaces, attributes, and processing exceptions.

 Exception
 https://docs.microsoft.com/en-us/dotnet/api/system.exception?view=netframework-2.0

 
 
 # ASP.Net
 
  postback
 
 https://www.codeproject.com/Articles/811684/Understanding-The-Complete-Story-of-Postback-in-AS
 
 PostBack is the name given to the process of submitting an ASP.NET page to the server for processing. PostBack is done if certain credentials of the page are to be checked against some sources (such as verification of username and password using database). This is something that a client machine is not able to accomplish and thus these details have to be 'posted back' to the server.

 A post back is round trip from the client (Browser) to the server and then back to the client. This enables you page to go through the asp engine on the server and any dynamic content to be updated.

