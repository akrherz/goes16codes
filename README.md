# GOES 16 Map Scripts

Generates the images found on [AOS Website](http://www.aos.wisc.edu/weather/wx_obs/GOES16_conus.html).

Here's a summary of the color tables and data transforms done for plotting
each channel.

<PRE>
Channel | Script                                           | Data Transform | Plot Range | Color Table | comments
    --- | ----                                             | ----           | ---        | --- 
 2      | `goes16_conus_visible_fixeddisk_latest.py`       | None           | 0-1        | `Greys_r`
 2      | `goes16_conus_visible_sqrt_fixeddisk_latest.py`  | None           | 0-1        | Custom
 4      | `goes16_conusc_cirrus_fixeddisk.py`              | None           | 0-1        | Custom
 5      | `goes16_conusc_snowice_fixeddisk.py`             | None           | 0-1        | Custom
 6      | `goes16_conusc_cldpartsize_fixeddisk.py`         | None           | 0-1        | Custom
 7      | `goes16_conusc_swir_fixeddisk.py`                | None           | 162-330    | Custom      | McIDAS color IR modified for fire
 8      | `goes16_conusc_wvh_fixeddisk.py`                 | None           | 162-330    | Custom      | color WV table
 9      | `goes16_conus_wv_fixeddisk.py`                   | None           | 162-330    | Custom      | greyscale WV table
 9      | `goes16_conusc_wvm_fixeddisk.py`                 | None           | 162-330    | Custom      | color WV table
10      | `goes16_conusc_wvl_fixeddisk.py`                 | None           | 162-330    | Custom      | color WV table
13      | `goes16_conus_ir13_fixeddisk.py`                 | None           | 162-330    | `Greys`     | greyscale IR table
14      | `goes16_conusc_ir_fixeddisk.py`                  | None           | 162-330    | Custom      | AWIPS2 color IR table
14      | `goes16_conusc_ircm_fixeddisk.py`                | None           | 162-330    | Custom      | McIDAS color IR table
</PRE>
