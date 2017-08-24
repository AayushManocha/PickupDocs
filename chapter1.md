# Developer Setup

## Local Environment Setup

Here's how to get the project \(current hosted on GitHub\) setup on your computer.

1. Firstly, make sure you have a GitHub account. 
2. The project can be found at [https://github.com/AayushManocha/Pickup](https://l.messenger.com/l.php?u=https%3A%2F%2Fgithub.com%2FAayushManocha%2FPickup&h=ATMook14CQKrjkHaKvFnBxCRNTIOWNDHBkfRNMKouASvneqnmdLWsVl7FsmXHGYfju-lygvgwlDB-7eO7jpNHmDbJRH16bxIK9oHczGST0lnETqro8mAP-Qoh-I3Sdic0C_BFNsjPn_vK6h_)
   1. Feel free to explore and ask questions!
3. Open the "Terminal" App on your Mac/Linux Computer
4. Paste the following commands

```bash
git clone https://github.com/AayushManocha/Pickup
```

This will "download" all the of the files and metadata associated with the master branch of the project

```
cd Pickup
npm install
```

This could take a while. These commands will navigate into the new project directory and install all development and production level project dependencies as listed in the package.json file. 

**If the second command doesn't work, ensure you have Node.js installed on your system. Download the latest stable release from nodejs.org**

## Mobile Phone Setup

There's only one thing you have to do run the app on your phone \(Thankfully\)

Go to the Apple App Store or the Google Play store and download the "Expo Client" Application

That's it!

## Testing The App

Now that you have everything setup, it's time to make sure everything is working

First open up your terminal and make sure you are in the Git Project's directory. Then run the following command

```
npm start
```

This could take a while. This will start a local dev web server to run the project from . Make sure your phone and computer are on the same WiFi network and then scan the QR code from your terminal within the Expo Client app on your phone. This should show you the bare minimum starter project that currently lives on the _master_ branch of the project.



All Done!

Let me know if you have any questions

-Aayush Manocha

