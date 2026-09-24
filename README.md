# navitals-brouter

Routing tiles (`.rd5`) for [BRouter](https://github.com/abrensch/brouter), used by the Navitals app
for on-device bicycle routing. They are mirrored from brouter.de's `segments4` so the app never
downloads from brouter.de itself.

- One rolling release, `tiles`, covering Europe (W25–E45, N35–N75). Tiles are replaced in place
  on each monthly update, so download URLs stay stable. Checksums are in the Navitals pack index.
- Total release size is kept under 5 GB.

Map data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors, available under
the Open Database License (ODbL). Tiles built by the BRouter project (MIT), brouter.de.
