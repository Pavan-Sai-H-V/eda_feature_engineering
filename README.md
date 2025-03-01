to use ipykernel and install
conda install -p c:\Users\PAVANS~1\Desktop\eda\venv ipykernel --update-deps --force-reinstall

when we get this error while reading .csv file (utf-8' codec can't decode byte 0xed in position 7044: invalid continuation byte)
use- encoder {df=pd.read_csv('zomato.csv',encoding='latin-1')}



count()-gives the total no of elements in a column
value_counts()-gives quantity of each category in a column



percentage formats

" %1.2f%% "
     after . write 2 decimal values