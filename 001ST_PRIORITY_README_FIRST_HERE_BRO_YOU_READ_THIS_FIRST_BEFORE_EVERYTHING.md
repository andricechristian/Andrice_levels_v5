"""
README_FIRST

Make yourself a service please read this fisrt

A)
This is for the file ANDRICE_LEVELS_v4 python code

cmd 1 : Is for how to Build RTH Sessions
cmd 2 : Is for how how to calculate RTH sessions levels

cmd 1 steps
1-run the code on cell 2 
2-upload your 1m OHLCV csv data
3-let him cook 
4-Save your new converted .csv data which contains the conversions

cmd 2steps
1- Run the code on cell 3
2- Download the 02_rth_levels. py file (I attached it to the github page)
3- Upload the 02_rth_levels.py file on the code
4- Upload your converted csv file which contains the RTH sessions
5- (optional) if you want you can also upload my csv file for RTH session it contains sessions 3699 rows(sessions) which is 16 + years of data 
7- After the calculations  just put the 9:30 open for today to plot the levels


B)
This is for the file README_ANDRICE_LEVELS_DETAILLED
It's a detailled readme for those who are good at math to understand the core concept of Andrice_Levels 

C) 
This is the file Docs_Understanding_Andrice_Levels
It's a docs to understand Maths concepts used for Andrice Levels if you are not good at it

D) 
This is for the file ES_RTH_Sessions_Updated
this is a converted RTH session convering 16 years of data : more than 3500 sessions

E)
This is for the files 01_build_rth_sessions_v2 and 02_calculate_rth_levels_v4
The file 01 is to import 1m or 5m OHLCV csv to convert it to the needed RTH sesions csv to do the calculations 
here's what the convertion is looking like :
what you import  .csv: date,time,open,high,low,close,volume 
it convert it to .csv: Session,Date,O_RTH,H_RTH,L_RTH,C_RTH,HOD_Time,LOD_Time,Extreme_First,PUV_Points,PDV_Points,PUV_Percent,PDV_Percent,RTH_Range_Points,Calendar_Days_Since_Previous_Complete,ATR_Sequence_Reset,Previous_Complete_RTH_Close,TR_RTH,ATR14_Previous,ATR14_End,PUV_ATR,PDV_ATR,RTH_Volume,Bar_Count,Duplicate_Bars


F)
This is for the file Andrice_RTH_Sessions_v1.2.jar 
This file is a Motivewvae Indicator for genereating a csv file that will contain this .csv : date,open,high,low,close,volume,lod_time,hod_time
you should always update your converted csv file for the rth sessions to the latest session

G)This is for the file Andrice_Levels_v2.1 
this is a pine script code for a Trading View Indicator when you paste the levels that the 02_calculate python code return it will automatically plot the areas needed 
"""
