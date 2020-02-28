{\rtf1\ansi\ansicpg1252\cocoartf1671\cocoasubrtf600
{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fnil\fcharset0 Menlo-Regular;}
{\colortbl;\red255\green255\blue255;\red62\green62\blue62;\red255\green255\blue255;\red27\green31\blue34;
\red244\green246\blue249;}
{\*\expandedcolortbl;;\cssrgb\c30980\c30980\c30980;\cssrgb\c100000\c100000\c100000;\cssrgb\c14118\c16078\c18039;
\cssrgb\c96471\c97255\c98039;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sl360\partightenfactor0

\f0\fs32 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 1. How did changing values on the SparkSession property parameters affect the throughput and latency of the data?\
\
It affected the processedRowPerSecond and inputRowsPerSecond\
\
2. What were the 2-3 most efficient SparkSession property key/value pairs? Through testing multiple variations on values, how can you tell these were the most optimal?\
\
\pard\pardeftab720\sl380\partightenfactor0

\f1\fs27\fsmilli13600 \cf4 \cb5 \strokec4 spark.streaming.kafka.maxRatePerPartition : 100\
spark.streaming.backpressure.enabled : true\
spark.default.parallelism : 100\
spark.sql.shuffle.partitions : 100\
}