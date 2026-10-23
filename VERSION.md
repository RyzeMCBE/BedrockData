# Datos para Minecraft Bedrock 1.26.52

Este fork contiene un unico conjunto activo de datos para el protocolo 2193. No selecciona archivos segun la version del jugador.

Referencia: `Mykoss/BedrockData@101371f542627f7f74ee1a2a86927ecd5d8bd553`. La paleta, los metadatos y los hashes proceden del conjunto emparejado 1.26.50 usado por RyzeMP para 2193; el diccionario de items corresponde a 1.26.51, del mismo protocolo. Estos archivos no se presentan como una captura independiente del cliente 1.26.52.

| Archivo activo | Archivo de referencia | SHA-256 |
| --- | --- | --- |
| `canonical_block_states.nbt` | `canonical_block_states-1.26.50.nbt` | `19e666a3c8b586575cbaeaa45e428139f5470f1e595969f827bf59eb162e1d0c` |
| `block_state_meta_map.json` | `block_state_meta_map-1.26.50.json` | `ef06f604008de23ce157a819464bb336e5c3152af18bea338ade3de5cf7920c7` |
| `block_network_ids.json` | `block_network_ids-1.26.50.json` | `840c1cb42913290a0785b719db74bd26a0302b1350df2bd84ac9575554766e8d` |
| `required_item_list.json` | `required_item_list-1.26.51.json` | `3ce35958b21f2341f6b8906bd011d29d60c929cc3299f97aabcfd3ff2a73f80c` |

Los tres archivos de bloques se deben actualizar juntos: su posicion enlaza el estado, su metadata y el hash de red firmado. Contienen 22 091 entradas cada uno.

El mapa de bloques a items conserva los identificadores usados por la persistencia de PocketMine. Esta actualizacion no cambia el formato de guardado de mundos ni incorpora las mecanicas adicionales de RyzeMP.
