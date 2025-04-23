### General
- [ ] Come up with final format for messages between back end front ends

### Frontend

- [ ] setup the most basic UI possible
- [ ] setup websockets
- [ ] create client states (Synced, Waiting, WaitingWithBuffer)
- [ ] implement OT logic (see [the link](https://github.com/Operational-Transformation/ot.hs/blob/master/src/Control/OperationalTransformation/Client.hs) (ignore the cursor))
- [ ] implement document updating

### Backend

- [ ] setup websockets
- [ ] setup in-memory queue (zio has them)
  - populate queue with data from websockets
  - pull data from it to process it with OT
- [ ] implement OT logic (see [the link](https://github.com/Operational-Transformation/ot.hs/blob/master/src/Control/OperationalTransformation/Server.hs) (ignore the cursor))
- [ ] implement sending changes back to clients


### Future
- document persistence
- multi document system

