# From Helm to an Internal Developer Platform

This repository contains the Helm chart used in [this blog post]().

The `main` branch includes a default Helm chart generated using the `helm create` command.

On the `add-schema` branch, a `values.schema.json` file has been added. This version was used to generate the **first** UI screenshot in the blog post using [Cyclops](https://github.com/cyclops-ui/cyclops).

The `edit-schema` branch contains an edited version of the `values.schema.json` file. This version was used to produce the **second** UI screenshot, showing how modifying the schema directly affects the generated interface.