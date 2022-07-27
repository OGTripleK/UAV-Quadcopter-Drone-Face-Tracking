# UAV Quadcopter Drone - Face Tracking
Created by Parsawit Deshwattanatham and Jessakorn Paopatimakorn under supervision of Professor Dr.Eng.Ryo Tanaka
________________________________________________________________________
Required Libraries
- pyqt5     `pip install pyqt5`
- pynput    `pip install pynput`
- numpy     `pip install numpy`
- cv2       `pip isntall cv2`
- djitellopy`pip install djitellopy` 
- threading `pip install threading`
________________________________________________________________________
### Content
- [Setting Up Guide](#instruction-on-how-to-use-script)
- [Drone Controller GUI guide](#drone-controller-gui-guide)
- [Auto Mode Instruction](#auto-mode-instruction)
- [Manual Mode Instruction](#manual-mode-instruction)
________________________________________________________________________
### Instruction on how to use script.

1.) Download final_v6.zip

![image](https://user-images.githubusercontent.com/77602952/181140108-322fd0b2-5233-4e03-9835-7ce31b25f993.png)

2.) Extract final_v6.zip

![image](https://user-images.githubusercontent.com/77602952/181140487-33c1589d-d1ad-45ab-adbc-eb7cc9f40937.png)

*** Note : Please put everything in same folder.

3.) Add Final_v6 folder into Exclusion of Window Defenders
- how to add folder to exclusion list --> [Click here](https://support.microsoft.com/en-us/windows/add-an-exclusion-to-windows-security-811816c0-4dfd-af4a-47e4-c301afe13b26#:~:text=Go%20to%20Start%20>%20Settings%20>%20Update,%2C%20file%20types%2C%20or%20process.)

![image](https://user-images.githubusercontent.com/77602952/181142651-ce9e274f-a101-4189-91e6-2bbe4f6f3512.png)

*** Note : We use keylogging method to grab keyboard input to control the drone. ***


4.) Turn on Tello drone and connect to Tello drone.

![image](https://user-images.githubusercontent.com/77602952/181142468-d93f6c25-938f-4d67-b398-af00697a0805.png)

5.) run main.py on any IDE.

![image](https://user-images.githubusercontent.com/77602952/181142041-aa04c031-0ae7-4b99-bb76-a76dfe338619.png)

6.) GUI will be shown right after script ran

![image](https://user-images.githubusercontent.com/77602952/181144106-9bc2aa05-6de7-4bf7-9343-085e86d65f23.png)
________________________________________________________________________

### Drone Controller GUI guide

- Battery and Temperature are displayed on top-right of the GUI.
![image](https://user-images.githubusercontent.com/77602952/181144538-da2b78fb-48cd-4e25-916c-e321d3af5ab1.png)

- Keymapping of Keyboard Control on Manual Mode.
![image](https://user-images.githubusercontent.com/77602952/181144754-ae7be6cd-0aa2-41df-a8fa-8c9def2acd39.png)

- Drone Speed Modifier on Manual Mode(50 / 75 / 100).
![image](https://user-images.githubusercontent.com/77602952/181144878-0feea131-06dc-4bd1-a015-c89bab2580ce.png)

- Global Control of both Auto and Manual Mode.
![image](https://user-images.githubusercontent.com/77602952/181157864-04eafc35-273f-4065-8474-96e4604f63d6.png)

- Safety Policy Check, Must be checked in order to connect to the drone.
![image](https://user-images.githubusercontent.com/77602952/181158252-f1ce41fc-45dd-458a-aaa0-55508c386abb.png)

- Control Method, Choose the way to control the drone (Default is Auto Mode).
![image](https://user-images.githubusercontent.com/77602952/181158473-b36f617d-f8dd-48ad-8d4e-74d6e1fdf9d4.png)

- Auto Take Off and Auto Landing, This only work on Auto Mode.
![image](https://user-images.githubusercontent.com/77602952/181158867-4e506af9-99a5-4070-ba72-b9b270f82ca4.png)

- Connect Drone Button, Use this to connect to drone with selected mode.
![image](https://user-images.githubusercontent.com/77602952/181159170-365fad48-bbd0-4568-94a5-486e01c19463.png)

- All drone information are shown on this section.
![image](https://user-images.githubusercontent.com/77602952/181163732-ef4b5d6d-bd5a-45eb-ac28-d666930f81f2.png)

- Drone Camera when connected are show in this section.
![image](https://user-images.githubusercontent.com/77602952/181164500-6ea91063-8e09-46cf-88be-0ffa7f2d62c9.png)
________________________________________________________________________
### Auto Mode Instruction
- Connect to tello drone and run main.py

![image](https://user-images.githubusercontent.com/77602952/181142468-d93f6c25-938f-4d67-b398-af00697a0805.png)
![image](https://user-images.githubusercontent.com/77602952/181142041-aa04c031-0ae7-4b99-bb76-a76dfe338619.png)

- Safety Check Policy must be all checked, then press connect.
![image](https://user-images.githubusercontent.com/77602952/181166100-7f74a078-7d6e-46ba-a4a0-c3e1fbf5e073.png)

- After camera are shown, click "Auto Mode Take Off / Landing" to take off
![image](https://user-images.githubusercontent.com/77602952/181166527-39ed6392-4e32-4603-bdb6-f26542a7afcd.png)

- After Drone take off, center your face at the middle of the drone camera and it will start tracking.
![image](https://user-images.githubusercontent.com/77602952/181167119-17118225-d955-437e-bf25-a16c85c6a659.png)

- To land the drone, click "Auto Mode Take Off / Landing" again to land.
![image](https://user-images.githubusercontent.com/77602952/181167402-9373afc5-065f-402e-8650-6248f0333597.png)

- To disconnect drone, click "Connect" button again to disconnect.
![image](https://user-images.githubusercontent.com/77602952/181167681-947898a0-220d-4884-8549-7cb6907400e5.png)
________________________________________________________________________
## Manual Mode Instruction
- Connect to tello drone and run main.py

![image](https://user-images.githubusercontent.com/77602952/181142468-d93f6c25-938f-4d67-b398-af00697a0805.png)
![image](https://user-images.githubusercontent.com/77602952/181142041-aa04c031-0ae7-4b99-bb76-a76dfe338619.png)

- Safety Check Policy must be all checked.

![image](https://user-images.githubusercontent.com/77602952/181172600-caa257f9-a7aa-4a7a-807a-f21f947e55da.png)

- Select Manual Mode.

![image](https://user-images.githubusercontent.com/77602952/181172669-969fd4d6-0127-46ca-aa1c-afbd7851baee.png)

- Click "Connect" button to connect to the drone.

![image](https://user-images.githubusercontent.com/77602952/181172740-a7ecb155-122e-4b3a-830a-a9a49f6456e8.png)

- After Connected, Use Keyboard to Control the drone. The Keymapping is shown in GUI.

![image](https://user-images.githubusercontent.com/77602952/181172912-445d3c06-f7fc-45f9-aad8-f6e31a1971d7.png)


