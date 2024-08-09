For create Supergraph build
ddn supergraph build local --output-dir engine --subgraph-env-file my_subgraph:my_subgraph/.env.my_subgraph.local

To host the api
set HASURA_DDN_PAT=$(ddn auth print-pat) && docker compose up --build --watch

