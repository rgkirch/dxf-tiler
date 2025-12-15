# Fusion 360 DXF Tiler

A browser-based tool designed to convert Fusion 360 (and other CAD) sketches into life-size, tiled PDF templates. This is ideal for woodworking, metalworking, and boat building where you need to print large-scale templates using a standard home printer (Letter/A4).

## 🚀 Key Features

* **1:1 Scale Printing:** Converts your CAD units (mm, cm, in, ft) directly to life-size PDF output.
* **Smart Tiling:** Automatically splits large drawings across multiple pages (Letter, Legal, Tabloid, A4, A3).
* **Paper Saving:** Intelligently detects and skips blank pages so you don't waste paper printing empty grid tiles.
* **Alignment Guides:** Auto-generates crop marks and overlap lines to make assembling your template easy.
* **Geometry Support:** Fully supports complex CAD entities including Lines, Polylines, Circles, Arcs, Splines, and Blocks.
* **Privacy:** All processing happens 100% in your browser. Your files are never uploaded to a server.

## 🛠️ How to Use

1.  **Export DXF:**
    * In Fusion 360, right-click on your Sketch in the browser tree and select **"Save as DXF"**.
2.  **Upload:**
    * Open this tool and drag & drop your `.dxf` file into the upload area.
3.  **Configure:**
    * Adjust the settings (explained below) to match your needs.
4.  **Preview:**
    * Check the "Estimated Output" section to see the total physical size and how many pages it will require.
5.  **Download:**
    * Click **"Download PDF"** to generate your printable document.

## ⚙️ Configuration Options

### Print Settings

* **Source Units:** Select the units used in your original CAD file (usually Millimeters for Fusion 360). This ensures the scale is correct.
* **Paper Size & Orientation:** Choose your printer's paper size. You can force Portrait/Landscape or let the app "Auto" detect the best fit.
* **Output Scale:** Keep this at **100%** for life-size templates. You can adjust it if you want to print a half-scale draft.
* **Line Thickness:** Use the slider to make lines thicker or thinner. Increasing thickness is recommended for cutting templates.

### Advanced Options

* **Skip Blank Pages:** When checked, the PDF will only contain pages that have actual drawing lines on them. Uncheck this if you want to print the entire empty grid for layout purposes.
* **Force Black Lines:** Ignores the colors defined in your DXF file and prints all lines in solid black. Useful if your CAD layer colors (like yellow or cyan) are hard to see on white paper.
* **Labels in Margin:** Moves the "Row 1, Col 1" text labels outside of the cut lines/printable area. This prevents the text from overlapping with your actual template.
* **Debug Mode:** Draws a red box around the calculated boundary of your geometry. Use this if you suspect parts of your drawing are being cut off or misplaced.

## 📄 License

This project is open-source. Feel free to use it for personal or commercial projects.
