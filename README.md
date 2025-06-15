# tableau-color-palettes
A) On your computer:
Open Notepad

Paste the following code:
From this: 

<?xml version='1.0'?>

<workbook>
  <preferences>

    <!-- My Blue-Green Palette -->
    <color-palette name="My Blue-Green Palette" type="regular"> 
      <color>#bbfdf3</color>
      <color>#a9e5db</color>
      <color>#88b9b1</color>
      <color>#77a19a</color>
      <color>#61837d</color>
      <color>#567570</color>
    </color-palette>

    <!-- Tableau 10 -->
    <color-palette name="Tableau 10" type="regular">
      <color>#4E79A7</color>
      <color>#F28E2B</color>
      <color>#E15759</color>
      <color>#76B7B2</color>
      <color>#59A14F</color>
      <color>#EDC949</color>
      <color>#AF7AA1</color>
      <color>#FF9DA7</color>
      <color>#9C755F</color>
      <color>#BAB0AC</color>
    </color-palette>

  </preferences>
</workbook>

till here please copy. Then : 

Click File → Save As

File name: Preferences.tps
File type: All Files (*.*)

Save to this location:

Copy code
Documents\My Tableau Repository\
🔁 3. Restart Tableau
After saving the file:

Completely close Tableau

Then open it again

Tableau reads the Preferences.tps file only at startup, so restarting is essential.

🎨 4. Use the Custom Palette in Tableau
Open a worksheet

Drag a dimension (like Category) onto the Color mark on the Marks card

Click Color → Edit Colors...

In the dropdown, find your custom palette:
Example: "My Blue-Green Palette"

Assign colors to values → click OK
