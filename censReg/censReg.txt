# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Censored Regression (Tobit) Models Use censReg With (In) R Software
install.packages("censReg")
install.packages("AER")
library("censReg")
censReg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/censReg/main/censReg/censReg.csv",sep = ";")
# Estimate Censored Regression (Tobit) Models Use censReg With (In) R Software
censReg <- censReg(Dependent ~ Independent_1 + Independent_2 + 
Independent_3 + Independent_4 + Independent_5 + Independent_6 + 
Independent_7 + Independent_8, data = censReg)
summary(censReg)
# Censored Regression (Tobit) Models Use censReg With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished