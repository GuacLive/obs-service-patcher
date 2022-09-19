# Guac OBS Service Patcher

This is a simple tool for making sure Guac.tv exists in the services list of your favorite OBS distribution. This tool adds Guac non-destructively by scanning the existing JSON file for the entry, and if it is not found, appending it to the bottom.

You may have to run this executable before each stream until the OBS Variant has Official Support.

| OBS Variant        | Patcher Support | Official Support | Notes                                                                                                                                               |
| ------------------ | --------------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| OBS Studio         | ✅              | ⛔️              | Pull request to OBS Studio repo has not been sent yet                                                                                               |
| Streamlabs Desktop | ✅              | ⛔️              | If you'd like official support please let Streamlabs know on the [Streamlabs Feature Request Board](https://ideas.streamlabs.com/ideas/SL-I-11481) |
