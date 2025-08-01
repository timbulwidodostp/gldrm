# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Semiparametric Generalized Linear Models Use gldrm With (In) R software
install.packages("gldrm")
library("gldrm")
gldrm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/gldrm/main/gldrm/gldrm.csv",sep = ";")
# Estimation Semiparametric Generalized Linear Models Use gldrm With (In) R software
gldrm <- gldrm(Dependen ~ Independen_1 + Independen_2 + Independen_3, data = gldrm, link = "log")
gldrm
# Semiparametric Generalized Linear Models Use gldrm With (In) R software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished