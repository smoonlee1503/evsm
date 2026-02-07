# evsm
Value Stream Mapper

React Value Stream Mapping (VSM) Tool

A web-based, drag-and-drop Value Stream Mapping tool built with React. This application allows users to visualize manufacturing processes, material flows, and information flows, while automatically calculating key metrics like Production Lead Time and Processing Time.

Features

Drag & Drop Interface: Easily add and move VSM symbols on an infinite canvas.

Comprehensive Icon Library:

Process: Manufacturing processes, Shared processes.

Material: Inventory, Supermarkets, Safety Buffers.

Transport: Trucks, Boats, Forklifts, Push/Pull arrows.

Information: Schedules, Kanban signals, Load Leveling, Electronic flow.

Automatic Calculations: Real-time calculation of Total Processing Time and Production Lead Time based on data entered in nodes.

Cloud Persistence: Save, load, and manage multiple projects using Firebase Firestore.

Interactive Canvas:

Zoom In/Out controls.

Panning (Hold Spacebar + Drag).

Snap-to-Grid for precise alignment.

Connection Modes: Support for both Manual (straight) and Electronic (lightning/zigzag) information flow lines.

Technologies Used

Frontend: React.js

Styling: Tailwind CSS

Icons: Lucide React

Backend/Storage: Firebase (Authentication & Firestore)
