# Testing issue 5623

A simple repro to test out multi tenancy on the auth emulator

1. Run `firebase emulators:start --export-on-exit=./users --import=./users --project demo-project` or `bash run.sh`
2. Open "http://localhost:5000/" in a web browser and follow the steps listed
