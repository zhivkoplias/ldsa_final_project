# ldsa_final_project

Perhaps test everything on the VM of Assignment 2 first?

## VM Usage

1. Clone this repository to get the key file `ldsa_lu.pem` 

2. Add

   ```
   Host ldsa_proj
   	HostName 130.238.29.135
   	User ubuntu
   	IdentityFile path/to/ldsa_lu.pem
   	LocalForward 8888 localhost:8888 
   	LocalForward 4040 localhost:4040
   	LocalForward 4041 localhost:4041
   	LocalForward 4042 localhost:4042
   	LocalForward 4043 localhost:4043
   ```

   to `~/.ssh/config` (`path/to` above needs to be replaced)

3. Run 

   ```bash
   ssh ldsa_proj
   ```

   to connect to the VM

4. Run 

   ```bash
   jupyter notebook
   ```

   to start coding

## TODO

- [ ] load dataset – ALL
- [ ] template for report – Anna
- [ ] coding – ALL
- [ ] report writing – TBD

## Done

- Prepared the presentation – Erik

- Set up VM with large flavour and 100GB volume - LU
- Installed pyspark-2.4.3 – LU
- Overleaf https://www.overleaf.com/8818127438cdhbxtjcwzdx - Anna
