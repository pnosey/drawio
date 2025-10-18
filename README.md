### How to apply drawio-config
1. Copy complete text from [drawio-config](https://github.com/pnosey/drawio/raw/main/drawio-config)
2. Open [draw.io](https://app.diagrams.net/)
3. Go to `Extras > Configuration...`
4. Paste copied text into `Configuration:` box
5. Click `Apply`

### This draw.io configuration will do the following:
- Set Preset Colors to HashiCorp product colors (Terraform, Packer, Vault, Waypoint, Nomad, Boundary, and Consul)
- Add Tooltips of the Product Names to their respective colors
- Add custom Color Schemes to the Style for Shapes corresponding with the HashiCorp product colors with a light grey outline
- Set default line color to same light grey as shape style outline
- Load the Scratchpad via url with a custom Flowchart Shape Library (HashiCorp_Shapes.xml) with normalized sizing across shapes.
- Set default page to landscape 8.5x11" aspect
- Set new blank diagram to dark grey background and page view off

You may need to clear the preferences in `Extras > Configuration... > Preferences > Reset` for Scratchpad to load.
