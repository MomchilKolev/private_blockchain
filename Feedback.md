# 1. Inaccessible /block/:hash

Since /block/:height is used, /block/:hash remains inaccessible, hence getBlockByHash cannot be tested, and by extension getBData, even though it's in the requirements.

- /block/height/:height and /block/hash/:hash
- /block?height=height and /block?hash=hash

# 2. Modify the 'getBlockHeight(hash)' function to retrieve a Block based on the hash parameter

No such function
Either `getBlockByHash(hash)` or `getBlockByHeight(height)`

- see 1. for a possible solutions

# 3. No way to run validateChain
