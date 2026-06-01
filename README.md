1. Project Overview
This project implements a fully responsive, modern Messages Directory Application using React Native for cross-platform deployment. The user interface strictly complies with the specification diagram provided by the instructor, presenting a symmetric 2×3 grid of iconic folder nodes: You, Home, Love, Family, Friends, and School.
The runtime infrastructure utilizes asynchronous state updates to toggle contextual modal overlays. Upon tapping any specific directory button, a native modal view sweeps upward from the bottom viewport, rendering a custom, distinct list of stored notifications simulated uniquely for this project to ensure independent data composition.
2. Project Structure
The implementation follows the clean, standard React Native architecture scaffolding. Below is the precise layout of the repository files included in the submission archive:

android/: Contains native build configurations and Gradle scripts to compile the Android binary.
android/local.properties: Defines local SDK path and maps system links for node/npm to prevent build failures.
App.tsx: The main application source file holding the UI layouts, styles, datasets, and responsive 2×3 grid logic.
package.json: Manages installed framework dependency versions and automation script definitions.

3. Core Environment Configurations & Dependencies
The software runtime utilizes the latest verified React Native CLI engine. Essential dependency nodes configured inside package.json include:
react: 18.x
react-native: 0.7x
Development environment managed via Node.js runtime and Android SDK platforms.
4. Step-by-Step Guide to Configure and Run
To execute this solution on a target device, follow the sequence below within the project root directory terminal:
Step 1: Initialize System Dependencies
Clean the initial packaging locks and execute the clean package synchronization:
npm install

Step 2: Establish Local Environment SDK Links
Ensure an absolute path mapping file named local.properties exists within the /android directory, pointing directly to the host Android SDK system layers:
sdk.dir=/Users/feifei/Library/Android/sdk
node.executable=/usr/local/bin/node
npm.executable=/usr/local/bin/npm
Step 3: Run the Local Metro Bundler Server
Spin up the background JavaScript compilation bridge server with an automatic cash flush mechanism:
PATH=$PATH:/usr/local/bin npx react-native run-android
5. Physical Screenshots


6. Conclusion
In summary, this project delivers a highly responsive Messages Directory Application built with React Native. By utilizing a centered 2×3 circular grid layout and removing top navigation bars, the UI achieves a premium aesthetic that perfectly matches the assignment specifications. All functional components, including custom datasets and dynamic bottom sheet modals, operate flawlessly. Crucially, the solution has been successfully deployed and verified on an actual mobile device, fulfilling all requirements for Exercise 3.

7. GitHub Repository URL: 
https://github.com/pao5200AI/REACT-NATIVE-MESSAGES-DIRECTORY

# REACT-NATIVE-MESSAGES-DIRECTORY
