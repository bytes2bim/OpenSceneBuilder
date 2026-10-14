# OpenSceneBuilder

I’m developing Open Scene Builder, an open source project bringing together a geometry kernel, an API, a 3D modeller and a new information schema (aligned to established standards).

Its native model format is MIB (Model Information Bundle), from the original term Model Information Building. The aim is to keep geometry, properties, relationships, supporting documents and model history together as work moves between people and tools.

The proposed MIB file carries its own viewer and, optionally, its modeller. Someone receiving it could open it in a supported browser, inspect the model and its information, and continue editing where the modelling tools are included. The data would remain readable independently of the bundled application.

Open Scene Builder has Git-like history: changes are recorded, commits mark useful points, and branches let you develop different design options from the same starting model. You can revisit earlier work and merge changes between branches, resolving conflicts explicitly. Local commits, branches and merges already work in the prototype. Visual comparison and collaboration between teams are next steps.

The schema and exchange tools are being designed around IFC, COBie and OpenUSD, with workflows intended to support ISO 19650 information management. Delivery profiles would support coordination, editable design transfer and handover, each tied to a specific model revision and defined requirements.

I’m looking for collaborators to help develop and test this: developers, designers, engineers, information managers and people who use asset information. Contributions could include code, exchange mappings, test models, practical requirements or feedback from trying it on real work.


Bytes2BIM (bytes2bim@gmail.com)

<img width="960" height="788" alt="image" src="https://github.com/user-attachments/assets/8c450020-171c-43d4-b610-a451b9a44e47" />

