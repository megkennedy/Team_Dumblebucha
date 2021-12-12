# Team_Dumblebucha
UW Fintech Bootcamp Project 2

Our project is to create a bot that will buy and sell crypto currency

The bot uses rolling averages and machine learning to attempt to predict when to buy and sell four crypto currencies. The crypto currencies are: BTC, ETH, LTC, and BCH; because we could do paper trades in alpaca with those coins. The data was pulled using yfiance.

## Libraries and dependencies needed

import pandas as pd

import numpy as np

from pathlib import Path

import hvplot.pandas

import matplotlib.pyplot as plt

from sklearn import svm

from sklearn.preprocessing import StandardScaler

from pandas.tseries.offsets import DateOffset

from sklearn.metrics import classification_report

import os

from dotenv import load_dotenv

import requests

import json

from getpass import getpass

import alpaca_trade_api as alpacaapi

import websocket

import _thread

import time

import yfinance as yf

## Issues

We attempted both SVM and LogisticRegression(notebook 2), however we couldn't find the combination that would get us more than 50% accuracy.
The notebooks run in both Jupyter Lab and GoogleColab. We used Google CoLab so that it would be easier for us to work in as a group.

## Project Members

Will Dittig

Jansen Eichenlaub

Meghan Kennedy

Daniel McCaffrey


As always a shout out to our professer, TAs, and classmates for all their help during this process
