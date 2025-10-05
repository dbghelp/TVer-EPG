# TVer-EPG
XML EPG for TVer channels

## Overview

This repository contains the XML EPG (Electronic Program Guide) for TVer channels. The EPG provides a schedule of the current and upcoming TV programs, enabling users to easily see what's on and plan their viewing.

Preview: https://dbghelp.github.io/epg.html?file=https://raw.githubusercontent.com/dbghelp/TVer-EPG/refs/heads/main/tver.xml

## Features

- XML formatted EPG for TVer channels
- Up-to-date information on channel programming
- Easy integration with various applications and services

## Usage

To use the EPG data, you can fetch the XML file from this repository and parse it in your application to display the program schedule.

In your M3U8 playlist, 

1. Change your url-tvg to "https://raw.githubusercontent.com/dbghelp/TVer-EPG/refs/heads/main/tver.xml":

```#EXTM3U url-tvg="https://raw.githubusercontent.com/dbghelp/TVer-EPG/refs/heads/main/tver.xml" refresh="3600"```

2. Change your tvg-id to the following for the respective channels:
  
| tvg-id                       | Channel Name                           |
|------------------------------|----------------------------------------|
| ntv    | 日テレ       |
| ex     | テレビ朝日   |
| tbs    | TBS          |
| tx     | テレ東       |
| cx     | フジテレビ   |
