perl_docset
===========
Generating dash docsets from local Perl POD files

Usage
-----------
```
./perl_docset [-i <input_directories>...] [-o <output_docset>] 
              [--id <CFBundleIdentifier>] [--name <CFBundleName>] [--family <DocSetPlatformFamily>]
```

<table>
    <th>
        <td>Default Value</td>
        <td>Notes</td>
    </th>
    <tr>
        <td>input</td>
        <td>the libraries of the current using perl executable</td>
        <td></td>
    </tr>
    <tr>
        <td>output</td>
        <td>Perl.docset</td>
        <td></td>
    </tr>
    <tr>
        <td>id</td>
        <td>Perl</td>
        <td></td>
    </tr>
    <tr>
        <td>name</td>
        <td>Perl</td>
        <td>display name in dash</td>
    </tr>
    <tr>
        <td>family</td>
        <td>Perl</td>
        <td>searching prefix (perl:)</td>
    </tr>
</table>


Dependencies
-----------
None

License
-----------
MIT
