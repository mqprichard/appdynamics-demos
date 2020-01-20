# Appdynamics Demo Projects
A collection of some of the many demo projects I built or managed whilst at AppDynamics, while leading the Sales Enablement and Online Demos team. These projects are archived from the originals, which are owned and maintained by AppDynamics. Some repos are private, because the originals are still in use at AppDynamics: some of these are public at the [AppDynamics GitHub site](https://github.com/Appdynamics), to which I was a major contributor.

[ECommerce-Docker](https://github.com/mqprichard/ECommerce-Docker) The kitchen sink demo project that I built to demonstrate key APM concepts.  The original demo app was monolithic: I broke it into separate modules and reworked these as Docker images, so the entire demo could be run from a laptop, although it was maintained as a cloud-based demo for 27/7 availability. The app supports both Web (Angular) and Mobile (iOS, Android) clients. The original version used plain Docker containers and scripted automation. Demo scenarios supported included core APM, Database Monitoring (Oracle and MySQL), Browser and Mobile RUM.

[AD-Capital](https://github.com/mqprichard/AD-Capital-Docker) A demo that I put together using Docker to illustrate the Transaction and Log Analytics features of the AppDynamics platform. I turned this demo into a container-based project using Docker: we later adapted it to use Kubernetes for the container orchestration.  Originally conceived as a financial service (loan processing) scenario, It was designed so that it could easily be tweaked to work in a variety of vertical industry contexts and these versions are all in use today by AppDynamics sales teams.

[AD-Capital-Kube](https://github.com/mqprichard/AD-Capital-Kube) We took the AD-Capital demo and showed how to convert a plain Docker project to run with Kubernetes.  The demo includes complete walkthrough instructions (see the project README file), and use of Keel and Helm for deployment. Eric and I used this project as the basis for a very successful series of technical webinars run by our Community team. 

Here are some of the webinars that featured this project:

* [Monitoring Kubernetes in the Cloud](https://community.appdynamics.com/t5/Knowledge-Base/Technical-Session-Monitoring-Kubernetes-in-the-Cloud-on-EKS-AKS/ta-p/33154)
* [Automating the Software Development Lifecycle](https://community.appdynamics.com/t5/Knowledge-Base/Technical-Session-Automating-the-Software-Development-Lifecycle/ta-p/33874)
* [Network Visiblity for Kubernetes](https://community.appdynamics.com/t5/Knowledge-Base/Technical-Session-Network-Visibility-for-Kubernetes/ta-p/34503)

[ECommerce-iOS](https://github.com/mqprichard/mark-ecommerce-ios) iOS demo client for the ECommerce demo. The project includes Objective-C and Swift versions, using CocoaPods. The project used XCode for automated testing. I used to run continuous tests using both simulators and actual iOS devices.

[ECommerce-Android](https://github.com/mqprichard/mark-ecommerce-android) Android demo client for the ECommerce demo.  The project uses Robotium for automated testing.  I used to run continuous tests using both AVD emulators and actual Android devices.

[ECommerce-Mobile- Tests](https://github.com/mqprichard/mark-ecommerce-mobile-tests) Mobile clients to test Mobile RUM beacon generation for the ECommerce application. These use a variety of languages and networking frameworks, with simple "bare-bones" user interfaces. Their primary purpose was to test beacon generation and server request correlation using the AppDynamics Mobile RUM Agents. The iOS clients included Objective-C and Swift versions, plus support for the AFNetworking framework.

[Telecom-Demo](https://github.com/mqprichard/Telecom-Demo) Another demo that I built to illustrate AppDYnamics Transaction and Log Analytics features. The app uses multiple container-based servers that simulate a telecom service ordering scenario.
