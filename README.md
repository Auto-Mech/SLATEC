# SLATEC

These files are from the SLATEC Common Mathematical Library, Version 4.1, July 1993.

### Installation using Conda

The most direct way to install the code is through the conda package manager.
If you have conda installed, simply run the following command in whichever
environment you choose:
```
conda install -c auto-mech slatec
```
If you do not have conda, it can be installed using the shell script
`debug/install-conda.sh`.

### Building from source without Conda

This is not the advised way to install, since the user will have to deal with their specific system setup.

Run build.sh, which uses cmake to compile SLATEC:
```
bash build.sh
```

Note that the results of the `make install` in build.sh will depend on your system setup.


## Notice 

Author:
Giuseppe Borzi'
e-mail: etana@tiscalinet.it
http://web.tiscalinet.it/gborzi
fax: +39 1782235968
Assistant Professor at the Univ. of Messina - Italia

License:
General Public License. Slatec is 'Freely distributable' as they say.

For further details, see <http://www.netlib.org/slatec/>.
