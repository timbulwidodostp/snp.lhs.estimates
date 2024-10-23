# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Logistic regression with SNP genotypes as dependent variable Use snp.lhs.estimates (snpStats) With (In) R Software
install.packages("https://raw.githubusercontent.com/timbulwidodostp/snp.lhs.estimates/main/snp.lhs.estimates/snpStats_1.54.0.zip", repos=NULL, type="source")
install.packages("https://raw.githubusercontent.com/timbulwidodostp/snp.lhs.estimates/main/snp.lhs.estimates/zlibbioc_1.50.0.zip", repos=NULL, type="source")
install.packages("https://raw.githubusercontent.com/timbulwidodostp/snp.lhs.estimates/main/snp.lhs.estimates/BiocGenerics_0.50.0.zip", repos=NULL, type="source")
library("snpStats")
snp_lhs_estimates = read.csv("https://raw.githubusercontent.com/timbulwidodostp/snp.lhs.estimates/main/snp.lhs.estimates/snp_lhs_estimates.csv",sep = ";")
# Estimation Logistic regression with SNP genotypes as dependent variable Use snp.lhs.estimates (snpStats) With (In) R Software
data(testdata)
snp.lhs.estimates <- snp.lhs.estimates(Autosomes[,1:3], ~cc, ~region, data=snp_lhs_estimates)
snp.lhs.estimates
# Logistic regression with SNP genotypes as dependent variable Use snp.lhs.estimates (snpStats) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
