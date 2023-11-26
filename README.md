# Polscriptions-Docs

Use Calldata to replace traditional smart contracts for data storage and transmission.

Transfer transactions of "From != To" and "From = To" generate polscriptions.

## How to create Polscriptions?

Convert an image (max size: ~90KB) to a Base 64-encoded data URI (data:image/png;base64,...) using a service like base64-image.de. The Polscriptions protocol supports all data URIs.
Convert the data URI to hex using an online tool like hexhero.
Send a 0 matic transaction to the person you want to own the Polscription with the hex data from (2) in the "Hex data" field.
After a few moments it should appear on this site, provided someone hasn’t already Polscribed the same data. Duplicate content is ignored!

## How to Transfer Polscriptions?

Find the id of the Polscription you want to transfer. An Polscription’s id is the transaction hash of the transaction that created the Polscription. It looks like this: 0xht32re4343545323fecdfvr344t45ft45t389ujfjd8389dju938d983d. You can get this from Polygonscan or from this site.
Send a 0 matic transaction to the new proposed owner, including the Polscription ID in the "Hex data" field.
After a few moments the Polscription’s owner should update on this site, provided you were the owner of the Polscription when you sent the transfer transaction. Unauthorized transfers are ignored.

## How to Track Polscriptions?

You can use polscriptions.com! However if you don’t want to rely on me you can track things yourself as all the necessary data is publicly available and uncensorable.
