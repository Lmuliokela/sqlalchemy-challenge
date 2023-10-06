# Sqlalchemy-Challenge

## Description
**Description:** The challenge was to imagine you decided to treat yourself to a long holiday vacation in Honolulu, Hawaii. To help with your trip planning, you decide to do a climate analysis about the area. You will need to use Python and SQLAlchemy to do a basic climate analysis and data exploration of your climate database. Specifically, you’ll use SQLAlchemy ORM queries, Pandas, and Matplotlib.

---

## Dependencies

%matplotlib inline

from matplotlib import style

style.use('fivethirtyeight')

import matplotlib.pyplot as plt

---
import numpy as np

import pandas as pd

import datetime as dt

---

Reflect Tables into SQLAlchemy ORM by;

import sqlalchemy

from sqlalchemy.ext.automap import automap_base

from sqlalchemy.orm import Session

from sqlalchemy import create_engine, func
