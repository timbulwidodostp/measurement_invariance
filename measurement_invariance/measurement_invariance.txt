# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Measurement invariance test Use measurement_invariance With (In) R Software
install.packages("remotes")
remotes::install_github("jasonmoy28/psycModel")
library("psycModel")
# Estimate Measurement invariance test Use measurement_invariance With (In) R Software
measurement_invariance = read.csv("https://raw.githubusercontent.com/timbulwidodostp/measurement_invariance/main/measurement_invariance/measurement_invariance.csv", sep = ";")
measurement_invariance(x1:x3, x4:x6, x7:x9, data = measurement_invariance, group = "school")
# Measurement invariance test Use measurement_invariance With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished