# Flashing RP2040 Uf2

## Save keymap before reset
If you already remap the keys, please save the layout before flashing.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/065aab39-79f1-4760-9bd2-b98c4af1aa54" width="600" style="border: 2px solid black;"/>
      <br>
      <em>Save keymap layout to be loaded later</em>
    </td>
  </tr>
</table>

### Split Keyboard
1. Get ready your compiled firmware or UF2 we provided.
2. Important notes: No QMK toolbox is required. You don’t need to unplug the cable between splits. You need to flash both sides with the same UF2.
3. Remap the `reset` key on your keymap under the `Quantum` tab. Double-press the `reset` key you just remapped twice.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/9e4e1f89-e0bb-41b1-8811-dc960348243f" width="600" style="border: 2px solid black;"/>
      <br>
      <em>Step 3: Remap the `reset` key in vial and double press it later</em>
    </td>
  </tr>
</table>

4. Proceed to step 4 only if step 3 is not working: Double-press the reset button between the OLED and TRS jack on the inside of the board.
5. A new window will pop out after you press the reset key. If it doesn't, try to press the reset key twice quickly.
6. Drag the UF2 file to the new window you just called out.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/superxc3/xcmkb/assets/79617315/b64efa1e-6ed9-47e8-b252-9e590b9865eb" width="600" style="border: 2px solid black;"/>
      <br>
      <em>A new window is called out and please drag the UF2 to the new window</em>
    </td>
  </tr>
</table>

7. Wait for about 5 seconds for the board to be flashed. When the key can be registered after you have dragged the file in, then it is done. You can also check the title of the vial to see whether the firmware name is correct.
8. That should be considered done for the left split. Continue the steps above for the right split.
9. Done!
10. Load the saved layout in Vial where you have saved your keymap.

Now you can start testing your new firmware. Have fun!

### Notes for SoflePLUS Trackpad V1.01 version
1. Please press `DPI0` after you flash your firmware to activate the trackpad.
2. Plugging in the USB to the left OLED shows WPM rocket, plugging in the USB to the right OLED shows overall status.
