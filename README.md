# reUKBB-GWAS
Documentation + code repo for our liftover and reformatting of existing UKBB-related GWAS

reUKBB-GWAS is an online resource consisting of lifted-over-to-GRCh38 (HG38) coordinate and specifically formatted-for-colocalization versions of the pre-existing various GWAS derived from the UK BioBank (UKBB) that are originally in GRCh37 (HG37) coordinates.  Specifically:
    - Approximately 8002 traits from the [Neal Lab](https://www.nealelab.is/uk-biobank)
    - [Imaging-based traits](https://open.oxcin.ox.ac.uk/ukbiobank/big40/) 
    - [Proteomics-based traits for EUR population](https://registry.opendata.aws/ukbppp/)
    These were lifted-over in bulk to be used in colocalization analysis.  The lifting over leveraged UCSC's liftover tool and *simply skipped* missing SNPs in HG38 (no special handling was done for specific-SNP issues).
