# Android NestDK

Android sample code using the Nest Firebase APIs and Nest oauth implementation.  This sample code also includes an Android wrapper library that abstracts the redirect URL authentication flow and Firebase APIs to create native Java objects to represent Thermostats, Structures and Smoke/CO alarms. To get started you'll need a Nest developer account and register a client.  When registering the client be sure to select the redirect URL authentication flow and select any URL of your choice. Be sure to update the Constants.java file within the testapp module with the client id, client secret and redirect URL respectively.

## Building

The project can be imported through Android Studio or Intellij by selecting File > Import Project and selecting the build.gradle file within the NestSamples directory

## Running

After importing the application, select 'run' and select any Android emulator or device that is running API level 14 (Ice Cream Sandwich, Android 4.0) or greater.

## Contributing

Contributions are always welcome and highly encouraged.

See [CONTRIBUTING](CONTRIBUTING.md) for more information on how to get started.

## License

Apache 2.0 - See [LICENSE](LICENSE) for more information.
