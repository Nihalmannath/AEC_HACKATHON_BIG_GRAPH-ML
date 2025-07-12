🧱 How to Run the Minecraft Server

Download TLauncher to run Minecraft.

Start the Server:
Open a terminal in the Minecraft folder and run the following command:

"java -Xms4G -Xmx6G -jar .\paper-1.21.4-232.jar nogui"

Replace the eula.txt, server.properties, and plugins folder with the provided versions.

Make sure these are placed inside the correct server directory when running.



🔁 Converting 3D Models to Schematics
Convert OBJ to Schematic:
Use objtoSchematic.exe to convert your .obj file.

Place the Schematic File:
After conversion, move the resulting schematic into:

pgsql
Copy
Edit
\Minecraft\paper-server\plugins\FastAsyncWorldEdit\schematic
  
