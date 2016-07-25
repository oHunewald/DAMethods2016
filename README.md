# Methods for differential abundance analyses of mass cytometry data

To repeat the analyses:

- Download the FCS files from Cytobank for accession number 43324, and put them in `refdata/Cytobank_43324`.
- Enter `refdata` and run `preprocess.R` to transform and gate on the intensities, followed by `gen_objects.R` to obtain the hypersphere counts.
