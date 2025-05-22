# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Velicer's minimum average partial (MAP) test Use MAP (EFA.dimensions) With (In) R Software
install.packages("EFA.dimensions")
library("EFA.dimensions")
MAP = read.csv("https://raw.githubusercontent.com/timbulwidodostp/MAP/main/MAP/MAP.csv",sep = ";")
# Estimation Velicer's minimum average partial (MAP) test Use MAP (EFA.dimensions) With (In) R Software
MAP <- data.frame(MAP$Height, MAP$Arm.span, MAP$Forearm, MAP$Leg.length, MAP$Weight, MAP$Hips, MAP$Chest.girth, MAP$Chest.width)
MAP(MAP, corkind='pearson', Ncases = 305, verbose=TRUE)
MAP(MAP, corkind='pearson', verbose=TRUE)
MAP(MAP, corkind='polychoric', verbose=TRUE)
MAP(MAP, verbose=TRUE)
# Velicer's minimum average partial (MAP) test Use MAP (EFA.dimensions) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished