# PT-Latest-Web
A Web Port of the Pizza Tower 1.10 Update (Noise Update) to the Web Browser. 

# How To Play (if you don't have a codespace):
Step 1: To have the web port working, go to Code, then click "Create new codespace on main".

Step 2: Do this command in the terminal: rm -rf * && gh release download r11 -R burnedpopcorn/Pizza-Tower-1.1.0-Web-Port -p PT_WebBuild_r11.7z && 7z x PT_WebBuild_r11.7z && rm PT_WebBuild_r11.7z Just make sure that you have the files before going to step 3: <img width="184" height="401" alt="Screenshot 2026-10-06 1 19 55 PM" src="https://github.com/user-attachments/assets/8251e651-5c6a-4b46-bf26-e244a3349a92" />


Step 3: Do this: python3 -m http.server 8080

It should work!
