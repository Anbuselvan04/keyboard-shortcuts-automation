# Exercise 9: Keyboard Automation - Simulate Keystrokes

### Reg No : 212221040013

## AIM: 
  To automate typing and simulating keyboard shortcuts in a desktop application.

## Activities Required:
  1. Use Application/Browser
  2. Type Into
  3. Send Hotkey

## Procedure:
  1. Open **Notepad** on your computer.
  
  2. Open **UiPath Studio** and create a new project called **KeyboardAutomation**.
  
  3. In the **Activities Panel**, search for **Use Application** and drag it into the **Designer Panel**.
  
  4. Set the **FileName** property of **Use Application** to `"notepad.exe"`.
  
  5. In the **Activities Panel**, search for **Type Into** and drag it below the **Use Application** activity.
  
  6. Set the **Text** property of the **Type Into** activity to `"This is an automated typing example."` for the notepad area.
  
  7. In the **Activities Panel**, search for **Send Hotkey** and drag it below the **Type Into** activity.
  
  8. Set the **Hotkey** property of the **Send Hotkey** activity to `Ctrl + S` to simulate saving the file.
  
  9. Save and Run the workflow.

## Workflow:
![image](https://github.com/user-attachments/assets/43e1f3bb-eaa4-482e-aa70-71c8ed5d9f22)

## Output:
![image](https://github.com/user-attachments/assets/ba3ae0a4-4c2d-4a70-98fc-cef115b54ab7)

## Result:
  Thus, the automation for simulating keystrokes and performing keyboard shortcuts is implemented successfully.
