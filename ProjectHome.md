# Goals #
  1. Write a chrome plugin based on native-client(NaCl).
  1. Migrate existing SDL project to NaCl including video and audio.

## Futures ##
  1. Streaming content
  1. nacl-mounts integration.

## Important ##
  1. It's a experiment and focus on realizing a media player through NaCl
  1. Run chrome without sandbox and set NACL\_DANGEROUS\_ENABLE\_FILE\_ACCESS=1 in order to grant access right to local files.
    * **[Mac\_10.7.5]** cmd>NACL\_DANGEROUS\_ENABLE\_FILE\_ACCESS=1 /Applications/Google Chrome.app/Contents/MacOS/Google\ Chrome --no-sandbox localhost:5103/ffnacl.html
    * **[Ubuntu\_12.10]** cmd>NACL\_DANGEROUS\_ENABLE\_FILE\_ACCESS=1 /opt/google/chrome --no-sandbox localhost:5103/ffnacl.html



