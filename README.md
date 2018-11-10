# NI-Web-Technology-Examples
We will look into what it takes to develop the basic components required to monitor and control system using NI Web Technology

# Example: Monitoring a simple Temperature Controller
I have embedded the quick demo of application through GIF below that shows the 3 components: LabVIEW application that generates data(in left), Web page streams the data (on right) and Web Service is shown in the LabVIEW project below.

![](https://boringengineer.com/wp-content/uploads/2018/07/Monitor-Temperature-Controller.gif)

# Different software pieces to build the Monitor and Control Systems
There are 3 components we need to get in place to achieve this and the below flow explains it.
![](https://boringengineer.com/wp-content/uploads/2018/07/Monitoring-Windows-Application.png)

The flow is from left to right: LabVIEW Web Service in the middle plays an important role that takes care of brokering between Windows application and Web page. The developer needs to clearly define and develop the sufficient HTTP Web Service APIs that is responsible to move data between the LabVIEW and Web. LabVIEW and WebVI then use the API’s to transfer and receive the data.

# Details on how to build this system is given [here](https://boringengineer.com/2018/07/29/ni-web-technology-monitor-and-control-systems/)
