# Secure Inter-Container Communication (ICC) Sample App for Cordova - Ionic

This sample application is written using the Ionic framework. It demonstrates using the BlackBerry Dynamics SDK for Cordova and Secure Inter-Container Communication (ICC). Features include:

* Getting Application Info from the management console.
* Creating and Sending files using Secure Inter-Container Communications.
* Composing secure emails to send via BlackBerry Work (or native email client if permitted by policy)
* Secure Storage Management

## Requirements
* Ionic 4 or later
* BlackBerry Dynamics Cordova SDK 6.0 or later

## Author(s)
* [Volodymyr Taliar](mailto:vtaliar@blackberry.com), [Taras Brateiko](mailto:tbrateiko@blackberry.com), [Taras Omelchuk](mailto:tomelchuk@blackberry.com)

**Contributing**
*   To contribute code to this repository you must be
    [signed up as an official contributor](http://blackberry.github.com/howToContribute.html).

## How To Build and Deploy
* Setup your BlackBerry Dynamics environment. See [Getting Started with Blackberry SDK for Cordova](https://docs.blackberry.com/en/development-tools/blackberry-dynamics-sdk-cordova/latest)
* In `<path>/BlackBerry-Dynamics-Cordova-Samples/Secure-ICC/config.xml` update paths to BlackBerry Dynamics Cordova plugins:
    - `spec` attribute of `plugin` tag for `cordova-plugin-bbd-*` should have a valid path 
    - replace `../..` with full path to `BlackBerry_Dynamics_SDK_for_Cordova_<version>` package
* `$ cd <path>/BlackBerry-Dynamics-Cordova-Samples/Secure-ICC`
* `$ npm i`
* For iOS:	
* `$ ionic cordova platform add ios`
* `$ ionic cordova build ios`
* AND/OR for Android:
* `$ ionic cordova platform add android`
* `$ ionic cordova build android`
* run the "SecureICC" application via IDE (Xcode/Android Studio) or using Ionic CLI 


For more information on BlackBerry Dynamics application development, visit the [BlackBerry Dynamics application developer website](https://developers.blackberry.com/dynamics)


## License

Apache 2.0 License


## Disclaimer

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

This sample pairs with Basic-iOS-Swift as examples of iOS apps before and after integrating with the BlackBerry Dynamics SDK. The two samples demostrate features commonly used in the BlackBerry Dynamics applications; secure file storage, secure database, secure communication (HTTP/S and Socket) and more.
