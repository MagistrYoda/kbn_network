# Network Plugin for Kibana 5, 6 and 7

This is a plugin developed for Kibana that displays a network node that link two fields that have been previously selected.

###### Link to the page: https://dlumbrer.github.io/kbn_network/

## Installation Steps from release

Now this plugin is avalible for differents versions of Kibana (6, 5 and 4), in [releases](https://github.com/dlumbrer/kbn_network/releases "Go to releases!") you can download the plugin with all its dependencies installed:

1. Go to [releases](https://github.com/dlumbrer/kbn_network/releases "Go to releases!") and download the right one for your Kibana
2. unzip/untar it into `KIBANA_HOME/plugins`
3. Start your Kibana


## Installation Steps from GitHub source code

1. Move into plugins folder:  `cd KIBANA_HOME/plugins`
2. Clone the source code (**it depends on your Kibana's version**):
    - Kibana 7.5 and upper: `git clone https://github.com/dlumbrer/kbn_network.git network_vis -b 7-dev`
    - Kibana 7.0 to 7.4: `git clone https://github.com/dlumbrer/kbn_network.git network_vis -b 7.4-dev`
    - Kibana 6.6 and upper: `git clone https://github.com/dlumbrer/kbn_network.git network_vis -b 6-dev`
    - Kibana 6.5: `git clone https://github.com/dlumbrer/kbn_network.git network_vis -b 6.5-dev`
    - Kibana 6.3 or 6.4: `git clone https://github.com/dlumbrer/kbn_network.git network_vis -b 6.4-dev`
    - Kibana 6.0, 6.1 or 6.2: `git clone https://github.com/dlumbrer/kbn_network.git network_vis -b 6.2-dev`
    - Kibana 5.5.X or 5.6.X: `git clone https://github.com/dlumbrer/kbn_network.git network_vis -b 5.5.x`
    - Kibana 5.5.X or lower: `git clone https://github.com/dlumbrer/kbn_network.git network_vis -b 5.4.x`
    - Kibana 4: `git clone https://github.com/dlumbrer/kbn_network.git network_vis -b 4.x`

3. Install dependencies:
      ```
      cd network_vis
      rm -rf images/
      npm install
      ```
4. Start Kibana

> **Important:** If you have any problem with the plugin version (like a warning message "**it expected Kibana version "x.x.x", and found "x.x.x"**") only change the value of the "version" tag on the package.json to your Kibana version


#### Uninstall:
```
cd KIBANA_HOME
rm -rf plugins/network_vis/
```


## Types of networks

#### Two types of Nodes:

It can select 'Node'-'Node' in buckets to show a network that link two types of nodes. Each type is the result of the field selected.

![Screenshot](images/Easy.png)

#### Nodes linked by a Relationship:

First, select 'Node' on buckets for build the network of one type of nodes, it depends of the field it has been selected. After, select 'Relation' to link the nodes through a relationship that depends of the field it has been selected.

![Screenshot](images/Types.png)

## Integration on Dashboard

Completly integration on Dashboards with other visualizations.

![Screenshot](images/Dashboard.png)

## User Guide

You can find an user guide in the file [USER_GUIDE.md](https://github.com/dlumbrer/kbn_network/blob/master/USER_GUIDE.md "Go to the user guide!")

## Help me to improve! :smile:

You can contact or helping me if you have any issue by:

- Opening an issue in the repository
- Opening a PR
- Sending an email to [me](mailto:dmorenolumb@gmail.com)!

This is an open source project that I maintain in my free time, as a hobby and my love for open source and data visualization. It is free as you know, but you can help me with a cup of coffee:

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HHPTP787VZVZL)
