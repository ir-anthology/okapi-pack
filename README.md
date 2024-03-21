# Okapi-Pack at ReNeuIR 2024

Work in progress. Preferred working environment via devcontainers, e.g., in Github Codespaces.
To start the github codespace, click on "Code" -> "Codespaces" -> "+ (Create Codespace)".

The okapi pack seems to come with the following command (have to figure out what they do):


### Command: i1+

```
i1+ --help
```

gives:
```
Usage: i1+ [-silent] [-exit_on_error|-e] [-f[lush]]
           -v[ersion]
           -h[elp]
  -silent eliminates the user prompt "U: "
  -flush flushes output after every command
  -exit_on_error causes an exit(1) if the BSS returns an error code
  -version outputs the BSS version number and date
```


### Command: ix1

```
ix1 --help
```

gives:

```
Usage: [-m[em] <mem>] [-t <tempdir> <minfree> [-t <tempdir> <minfree>]]
[-h[elp]] [-s[tart] <start_rec>] [-f[inish] <finish_rec>] [-silent]
[-quiet] [-d[ebug] <debug code>] [-c <control path>] [-maxruns <num>]
[-[no]index] [-[no]doclens] [-termunit] [-[no]merge]
[-[no]deltmp] [-[no]delfinal] [-l[im] limit mask] [-mmap [-mlock]]
<database> <index number> > <output file>

Database name and index number must be the last two args, otherwise order
is unimportant.
```

### Command: ixf

```
ixf --help
```

```
Usage: ixf [-c <control directory>] [-no_out] [-diag] [-silent]
[-stdout {sends posting file to stdout}] [-version] [-help]
[-report <reportlevel>] <database> <index number (0..15)>
Database name and index number must come last.
```

### Command: xml_path

```
xml_path --help
```

Gives:
```
pls input the des database, input stem, number of bib files, record tag and record tag level!
 eg:  xml_path inex05.xml i:\inex\inex-1.6\inex05.xml 2 article 3
```


### Command: convert_runtime

```
convert_runtime
```

gives:
```
Usage: convert_runtime [-c <ctrl directory>] [-a] [-num <maxrecs>]
[-treclimits] [-fixedlimit <fixedlim>] [-halfcollection] [-version] [-help]
[-rm <record terminator character>] [-fm <field terminator character>]
[-phoney_fcno] [-skip <skipnum>] [-checkpoint <interval>] [-nopar]
[-silent] <database name> < <input file>
```