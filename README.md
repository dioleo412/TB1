# TB1
Business Process IntelligenceMounted at /content/drive
# Import library
import pandas as pd
import numpy as np
#from datetime import date
from IPython.display import Image
pd.options.mode.chained_assignment = None  # default='warn'
%ls
drive/  sample_data/
# import dataset kedalam program python
event_df = pd.read_csv('drive/MyDrive/ProcessMiningResearch/ver20_bersih.csv', sep=',', low_memory=False)
# Melihat Ringkasan dataset
event_df.head()
# mengkoneksikan colab dengan google drive
from google.colab import drive
drive.mount('/content/drive')Mounted at /content/drive
# Import library
import pandas as pd
import numpy as np
#from datetime import date
from IPython.display import Image
pd.options.mode.chained_assignment = None  # default='warn'
%ls
drive/  sample_data/
# import dataset kedalam program python
event_df = pd.read_csv('drive/MyDrive/ProcessMiningResearch/ver20_bersih.csv', sep=',', low_memory=False)
# Melihat Ringkasan dataset
event_df.head()
