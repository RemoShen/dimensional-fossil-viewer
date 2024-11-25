# DimensionalFossilViewer

This library was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.2.0.

## 1. Component Overview

`DimensionalFossilViewerComponent` is a feature-rich component designed to load and display 3D fossil models, offering various interactive tools for viewing and analyzing the models. The main features supported by this component include:

- **Model and Texture Loading**: Allows the loading of 3D models and their textures.
- **3D View Controls**: Provides controls for rotating, zooming, and translating the model.
- **Tool Toggles**: Includes tools for length, area, and depth analysis.
- **Graphical Helpers**: Displays additional tools such as grids, axes, and normals.
- **Responsive Window Resizing**: Adjusts the view based on window size changes.
- **Data Statistics**: Provides statistical data such as total length, total area, etc.

## 2. Inputs and Outputs

### Inputs:
- **modelPath**: The path to the 3D model to be loaded.
- **texturePath**: The path to the texture for the model.

### Outputs:
- **fossilselected**: Emitted when the user selects a fossil model, passing the selected fossil object.

## 3. View Child Components

The component uses multiple child components to manage different functional modules:

- **ControlsComponent**: Handles 3D view controls such as rotation, zoom, and pan.
- **InteractionsComponent**: Manages interactions with the model, such as click events and tool activations.
- **ModelLoaderComponent**: Responsible for loading the 3D model and texture.
- **HelpersComponent**: Provides additional helper tools, such as displaying grids, axes, and normals.
- **HistogramComponent**: Displays histograms of data used for analyzing specific properties of the model.