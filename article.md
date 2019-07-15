---
template: dossier
auto: true
feed: true
gallery: true
title: Klimawandel
subject: ''
description: ''
slug: klimawandel
---

<section><h6>TITLE</h6>

# Klimawandel

## 

⁣

Von [Andreas Moor](/~65b64225-3843-4e41-a7a6-716ae81a5d57), 21.05.2019

<hr /></section>

<section><h6>CENTER</h6>

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesqueeu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo,fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut,imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.Integer tincidunt. 

<section><h6>DYNAMIC_COMPONENT</h6>

```
{
  "autoHtml": true,
  "props": {
    "values": [
      {
        "label": "CO₂-Dichte",
        "value": 441,
        "unit": "ppm",
        "description": "Millionstel CO₂-Moleküle in der Atmosphäre.",
        "source": {
          "name": "NASA",
          "url": "https://climate.nasa.gov/vital-signs/carbon-dioxide/",
          "date": "Mai 2019"
        },
        "color": "rgb(187,21,26)"
      },
      {
        "label": "Veränderung seit 2005",
        "value": "+5.5",
        "unit": "Prozent",
        "description": "Zunahme der CO₂-Dichte in der Athmosphäre",
        "color": "rgb(187,21,26)"
      },
      {
        "label": "CO₂-Austoss pro Kopf",
        "value": "4.97",
        "unit": "Tonnen",
        "color": "rgb(187,21,26)"
      },
      {
        "label": "Temperaturanstieg seit 2005",
        "value": "+0.8",
        "unit": "Grad Celsius",
        "color": "rgb(8,48,107)"
      }
    ]
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/indicators.js?v2"
}
```

<hr /></section>

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesqueeu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo,fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut,imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.Integer tincidunt. 

<section><h6>CHART</h6>

```
{
  "type": "TimeBar",
  "y": "label",
  "color": "label",
  "xTicks": [
    1960,
    1970,
    1980,
    1990,
    2000,
    2010,
    2017
  ],
  "unit": "Millionen Tonnen CO2"
}
```

### Stetige Zunahme

Weltweiter jährlicher CO₂-Ausstoss nach Regionen

```
year,label,value
1960,China,778.9795
1960,USA,2887.8204
1960,EU28,2645.1884
1960,Andere,3098.5415
1961,China,550.9585
1961,USA,2877.3698
1961,EU28,2739.4012
1961,Andere,3284.3782
1962,China,439.3421
1962,USA,2984.0017
1962,EU28,2898.2039
1962,Andere,3516.6544
1963,China,435.5176
1963,USA,3116.0224
1963,EU28,3096.1111
1963,Andere,3731.4169
1964,China,435.7037
1964,USA,3252.7552
1964,EU28,3211.2394
1964,Andere,4069.6268
1965,China,474.6806
1965,USA,3388.1927
1965,EU28,3269.2360
1965,Andere,4334.0409
1966,China,521.4589
1966,USA,3559.1792
1966,EU28,3324.3221
1966,Andere,4640.5957
1967,China,432.2236
1967,USA,3693.2982
1967,EU28,3359.6221
1967,Andere,4945.8655
1968,China,467.8056
1968,USA,3828.3061
1968,EU28,3545.7508
1968,Andere,5221.5871
1969,China,575.9447
1969,USA,4021.5026
1969,EU28,3768.9410
1969,Andere,5480.0390
1970,China,770.1672
1970,USA,4325.5008
1970,EU28,3940.2237
1970,Andere,5809.9233
1971,China,874.0164
1971,USA,4351.3087
1971,EU28,4031.1005
1971,Andere,6153.2920
1972,China,928.8940
1972,USA,4558.4526
1972,EU28,4145.6879
1972,Andere,6390.9563
1973,China,965.6466
1973,USA,4762.4522
1973,EU28,4340.5579
1973,Andere,6824.7047
1974,China,985.0852
1974,USA,4592.9583
1974,EU28,4278.3988
1974,Andere,7067.1364
1975,China,1142.1019
1975,USA,4400.7950
1975,EU28,4176.7062
1975,Andere,7106.0379
1976,China,1190.9645
1976,USA,4607.1682
1976,EU28,4464.2837
1976,Andere,7538.5560
1977,China,1304.4028
1977,USA,4735.3663
1977,EU28,4422.4613
1977,Andere,7893.2088
1978,China,1455.2575
1978,USA,4882.9640
1978,EU28,4555.2832
1978,Andere,7668.1942
1979,China,1487.1131
1979,USA,4894.0429
1979,EU28,4724.4993
1979,Andere,8488.5735
1980,China,1458.8867
1980,USA,4716.7164
1980,EU28,4619.0847
1980,Andere,8593.4066
1981,China,1442.7823
1981,USA,4530.3698
1981,EU28,4388.2249
1981,Andere,8425.7456
1982,China,1570.4683
1982,USA,4301.9707
1982,EU28,4284.7793
1982,Andere,8466.8574
1983,China,1655.8105
1983,USA,4335.9166
1983,EU28,4241.6611
1983,Andere,8316.0598
1984,China,1802.3171
1984,USA,4468.2620
1984,EU28,4254.7596
1984,Andere,8691.5273
1985,China,1951.7732
1985,USA,4484.3382
1985,EU28,4341.6387
1985,Andere,9014.8717
1986,China,2052.2420
1986,USA,4487.8558
1986,EU28,4340.9984
1986,Andere,9514.8533
1987,China,2191.0530
1987,USA,4680.8341
1987,EU28,4382.6172
1987,Andere,9657.9092
1988,China,2347.7635
1988,USA,4885.5905
1988,EU28,4338.4472
1988,Andere,10109.3081
1989,China,2386.8850
1989,USA,4948.0212
1989,EU28,4396.9674
1989,Andere,10422.4621
1990,China,2420.3021
1990,USA,5121.2645
1990,EU28,4479.3289
1990,Andere,10160.9119
1991,China,2538.9240
1991,USA,5070.8394
1991,EU28,4423.0245
1991,Andere,10396.5895
1992,China,2657.1124
1992,USA,5174.0591
1992,EU28,4278.9581
1992,Andere,10084.9755
1993,China,2835.7955
1993,USA,5284.6879
1993,EU28,4194.9737
1993,Andere,9837.6860
1994,China,3010.2422
1994,USA,5377.9871
1994,EU28,4174.4997
1994,Andere,9971.1040
1995,China,3265.0570
1995,USA,5439.2133
1995,EU28,4221.4647
1995,Andere,10081.6904
1996,China,3408.3466
1996,USA,5626.1867
1996,EU28,4325.0739
1996,Andere,10163.3719
1997,China,3414.5493
1997,USA,5703.8907
1997,EU28,4235.9323
1997,Andere,10560.9571
1998,China,3265.9026
1998,USA,5752.3242
1998,EU28,4228.9864
1998,Andere,10737.7707
1999,China,3258.1349
1999,USA,5832.2502
1999,EU28,4164.1472
1999,Andere,10676.0292
2000,China,3349.2948
2000,USA,6000.6061
2000,EU28,4187.3341
2000,Andere,11021.4561
2001,China,3426.1441
2001,USA,5902.4550
2001,EU28,4259.4002
2001,Andere,11550.0004
2002,China,3782.4393
2002,USA,5943.6513
2002,EU28,4235.8145
2002,Andere,11532.2855
2003,China,4452.3103
2003,USA,5991.3196
2003,EU28,4327.7817
2003,Andere,12095.3268
2004,China,5125.8944
2004,USA,6106.6207
2004,EU28,4337.9729
2004,Andere,12617.1109
2005,China,5771.1684
2005,USA,6132.0057
2005,EU28,4314.6397
2005,Andere,13037.0926
2006,China,6377.7480
2006,USA,6052.2363
2006,EU28,4320.4097
2006,Andere,13536.4424
2007,China,6861.7507
2007,USA,6130.9836
2007,EU28,4274.4088
2007,Andere,13613.0022
2008,China,7375.1899
2008,USA,5932.7753
2008,EU28,4173.8625
2008,Andere,14393.9281
2009,China,7758.8118
2009,USA,5495.3950
2009,EU28,3831.8294
2009,Andere,14437.1068
2010,China,8500.5427
2010,USA,5701.0758
2010,EU28,3951.2626
2010,Andere,14913.7701
2011,China,9388.1992
2011,USA,5570.7066
2011,EU28,3805.9612
2011,Andere,15592.4989
2012,China,9633.8993
2012,USA,5366.7303
2012,EU28,3747.2409
2012,Andere,16171.4182
2013,China,9796.5272
2013,USA,5519.6126
2013,EU28,3659.2409
2013,Andere,16232.5053
2014,China,9820.3605
2014,USA,5568.7593
2014,EU28,3490.3832
2014,Andere,16626.3240
2015,China,9716.4678
2015,USA,5420.8041
2015,EU28,3523.4918
2015,Andere,16801.9830
2016,China,9704.4794
2016,USA,5310.8614
2016,EU28,3503.0312
2016,Andere,17156.7274
2017,China,9838.7540
2017,USA,5269.5295
2017,EU28,3543.6835
2017,Andere,17501.2946
```

Quelle: Carbon Atlas

<hr /></section>

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesqueeu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo,fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut,imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputateeleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac,enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellusviverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiamultricies nisi vel augue.

<section><h6>CHART</h6>

```
{
  "type": "Line",
  "color": "category",
  "numberFormat": ".1f",
  "x": "year",
  "xScale": "ordinal",
  "xSort": "none",
  "colorSort": "none",
  "yNice": 0,
  "yTicks": [
    -8,
    -4,
    0,
    4,
    8,
    12
  ],
  "size": "breakout",
  "xTicks": [
    "-500k",
    "-250k",
    "2018"
  ],
  "unit": "Grad Celsius",
  "colorRange": [
    "rgb(8,48,107)",
    "rgb(187,21,26)"
  ],
  "endLabel": false
}
```

### It’s a match!

Temperaturen und CO<sub>2</sub>-Konzentration

```
year,category,value
-500k,Temperatur,-2.4
-499000,Temperatur,-2.48
-498000,Temperatur,-2.53
-497000,Temperatur,-2.54
-496000,Temperatur,-2.43
-495000,Temperatur,-2.4
-494000,Temperatur,-2.35
-493000,Temperatur,-2.15
-492000,Temperatur,-2.01
-491000,Temperatur,-2.14
-490000,Temperatur,-2.36
-489000,Temperatur,-2.43
-488000,Temperatur,-2.76
-487000,Temperatur,-2.98
-486000,Temperatur,-3.19
-485000,Temperatur,-3.35
-484000,Temperatur,-3.42
-483000,Temperatur,-3.5
-482000,Temperatur,-3.67
-481000,Temperatur,-4.27
-480000,Temperatur,-4.66
-479000,Temperatur,-5.03
-478000,Temperatur,-5.32
-477000,Temperatur,-5.54
-476000,Temperatur,-5.62
-475000,Temperatur,-5.91
-474000,Temperatur,-6.04
-473000,Temperatur,-5.92
-472000,Temperatur,-6
-471000,Temperatur,-6.06
-470000,Temperatur,-6.03
-469000,Temperatur,-6.13
-468000,Temperatur,-6.2
-467000,Temperatur,-6.26
-466000,Temperatur,-6.23
-465000,Temperatur,-6.12
-464000,Temperatur,-5.96
-463000,Temperatur,-5.91
-462000,Temperatur,-5.88
-461000,Temperatur,-5.88
-460000,Temperatur,-6.11
-459000,Temperatur,-6.41
-458000,Temperatur,-6.56
-457000,Temperatur,-5.57
-456000,Temperatur,-5.58
-455000,Temperatur,-5.34
-454000,Temperatur,-5.28
-453000,Temperatur,-5.36
-452000,Temperatur,-5.12
-451000,Temperatur,-5.13
-450000,Temperatur,-5.01
-449000,Temperatur,-4.96
-448000,Temperatur,-5.09
-447000,Temperatur,-5.02
-446000,Temperatur,-4.9
-445000,Temperatur,-4.95
-444000,Temperatur,-4.92
-443000,Temperatur,-4.56
-442000,Temperatur,-4.54
-441000,Temperatur,-4.57
-440000,Temperatur,-4.73
-439000,Temperatur,-5.02
-438000,Temperatur,-5.21
-437000,Temperatur,-5.28
-436000,Temperatur,-5.33
-435000,Temperatur,-5.18
-434000,Temperatur,-5.07
-433000,Temperatur,-4.9
-432000,Temperatur,-4.69
-431000,Temperatur,-4.73
-430000,Temperatur,-4.49
-429000,Temperatur,-4.49
-428000,Temperatur,-4.23
-427000,Temperatur,-4.09
-426000,Temperatur,-3.78
-425000,Temperatur,-3.52
-424000,Temperatur,-3.25
-423000,Temperatur,-2.63
-422000,Temperatur,-1.99
-421000,Temperatur,-1.61
-420000,Temperatur,-1.36
-419000,Temperatur,-0.91
-418000,Temperatur,-0.62
-417000,Temperatur,-0.46
-416000,Temperatur,-0.29
-415000,Temperatur,-0.2
-414000,Temperatur,-0.17
-413000,Temperatur,-0.07
-412000,Temperatur,0.01
-411000,Temperatur,0.18
-410000,Temperatur,0.31
-409000,Temperatur,0.25
-408000,Temperatur,0.39
-407000,Temperatur,0.44
-406000,Temperatur,0.4
-405000,Temperatur,0.21
-404000,Temperatur,0.19
-403000,Temperatur,0.17
-402000,Temperatur,-0.12
-401000,Temperatur,-0.13
-400000,Temperatur,-0.31
-399000,Temperatur,-0.76
-398000,Temperatur,-1.02
-397000,Temperatur,-1.21
-396000,Temperatur,-1.35
-395000,Temperatur,-1.57
-394000,Temperatur,-2.01
-393000,Temperatur,-2.14
-392000,Temperatur,-2.37
-391000,Temperatur,-2.83
-390000,Temperatur,-3.24
-389000,Temperatur,-3.29
-388000,Temperatur,-3.36
-387000,Temperatur,-3.5
-386000,Temperatur,-3.54
-385000,Temperatur,-3.74
-384000,Temperatur,-4.01
-383000,Temperatur,-4.1
-382000,Temperatur,-4.01
-381000,Temperatur,-4.2
-380000,Temperatur,-4.4
-379000,Temperatur,-4.42
-378000,Temperatur,-4.58
-377000,Temperatur,-4.68
-376000,Temperatur,-4.73
-375000,Temperatur,-4.8
-374000,Temperatur,-5.01
-373000,Temperatur,-5.24
-372000,Temperatur,-5.46
-371000,Temperatur,-5.48
-370000,Temperatur,-5.43
-369000,Temperatur,-5.39
-368000,Temperatur,-5.54
-367000,Temperatur,-5.77
-366000,Temperatur,-5.9
-365000,Temperatur,-5.99
-364000,Temperatur,-6.22
-363000,Temperatur,-6.3
-362000,Temperatur,-6.2
-361000,Temperatur,-6.16
-360000,Temperatur,-5.97
-359000,Temperatur,-5.83
-358000,Temperatur,-5.57
-357000,Temperatur,-5.6
-356000,Temperatur,-5.59
-355000,Temperatur,-5.64
-354000,Temperatur,-5.66
-353000,Temperatur,-5.72
-352000,Temperatur,-5.71
-351000,Temperatur,-5.69
-350000,Temperatur,-5.81
-349000,Temperatur,-5.72
-348000,Temperatur,-5.63
-347000,Temperatur,-5.59
-346000,Temperatur,-5.52
-345000,Temperatur,-5.4
-344000,Temperatur,-5.36
-343000,Temperatur,-5.14
-342000,Temperatur,-4.87
-341000,Temperatur,-4.35
-340000,Temperatur,-3.76
-339000,Temperatur,-3.25
-338000,Temperatur,-2.57
-337000,Temperatur,-2.19
-336000,Temperatur,-1.94
-335000,Temperatur,-1.46
-334000,Temperatur,-0.93
-333000,Temperatur,-0.45
-332000,Temperatur,-0.02
-331000,Temperatur,0.17
-330000,Temperatur,0.26
-329000,Temperatur,0.11
-328000,Temperatur,0.1
-327000,Temperatur,0
-326000,Temperatur,0.06
-325000,Temperatur,0.03
-324000,Temperatur,-0.15
-323000,Temperatur,-0.42
-322000,Temperatur,-0.64
-321000,Temperatur,-0.8
-320000,Temperatur,-1.12
-319000,Temperatur,-1.36
-318000,Temperatur,-1.58
-317000,Temperatur,-1.74
-316000,Temperatur,-1.86
-315000,Temperatur,-1.92
-314000,Temperatur,-1.96
-313000,Temperatur,-2.08
-312000,Temperatur,-2.21
-311000,Temperatur,-2.31
-310000,Temperatur,-2.37
-309000,Temperatur,-2.33
-308000,Temperatur,-2.51
-307000,Temperatur,-2.65
-306000,Temperatur,-2.76
-305000,Temperatur,-2.88
-304000,Temperatur,-3.04
-303000,Temperatur,-3.35
-302000,Temperatur,-3.43
-301000,Temperatur,-3.7
-300000,Temperatur,-3.8
-299000,Temperatur,-3.94
-298000,Temperatur,-3.97
-297000,Temperatur,-4.09
-296000,Temperatur,-4.26
-295000,Temperatur,-4.41
-294000,Temperatur,-4.52
-293000,Temperatur,-4.62
-292000,Temperatur,-4.59
-291000,Temperatur,-4.26
-290000,Temperatur,-3.94
-289000,Temperatur,-3.74
-288000,Temperatur,-3.5
-287000,Temperatur,-3.13
-286000,Temperatur,-2.75
-285000,Temperatur,-2.65
-284000,Temperatur,-2.73
-283000,Temperatur,-2.96
-282000,Temperatur,-3.29
-281000,Temperatur,-3.77
-280000,Temperatur,-4.13
-279000,Temperatur,-4.34
-278000,Temperatur,-4.55
-277000,Temperatur,-4.65
-276000,Temperatur,-4.69
-275000,Temperatur,-4.71
-274000,Temperatur,-4.92
-273000,Temperatur,-5.18
-272000,Temperatur,-5.33
-271000,Temperatur,-5.34
-270000,Temperatur,-5.44
-269000,Temperatur,-5.45
-268000,Temperatur,-5.2
-267000,Temperatur,-5.24
-266000,Temperatur,-5.24
-265000,Temperatur,-5.31
-264000,Temperatur,-5.44
-263000,Temperatur,-5.28
-262000,Temperatur,-5.22
-261000,Temperatur,-4.95
-260000,Temperatur,-4.71
-259000,Temperatur,-4.85
-258000,Temperatur,-4.94
-257000,Temperatur,-4.94
-256000,Temperatur,-5.14
-255000,Temperatur,-5.13
-254000,Temperatur,-5.15
-253000,Temperatur,-5.16
-252000,Temperatur,-5.25
-251000,Temperatur,-5.13
-250k,Temperatur,-5.16
-249000,Temperatur,-5.26
-248000,Temperatur,-5.18
-247000,Temperatur,-4.98
-246000,Temperatur,-4.78
-245000,Temperatur,-4.49
-244000,Temperatur,-3.99
-243000,Temperatur,-3.5
-242000,Temperatur,-3.06
-241000,Temperatur,-2.66
-240000,Temperatur,-2.36
-239000,Temperatur,-2.09
-238000,Temperatur,-1.84
-237000,Temperatur,-1.54
-236000,Temperatur,-1.33
-235000,Temperatur,-1.22
-234000,Temperatur,-1.21
-233000,Temperatur,-1.45
-232000,Temperatur,-1.73
-231000,Temperatur,-1.92
-230000,Temperatur,-2.27
-229000,Temperatur,-2.6
-228000,Temperatur,-3.1
-227000,Temperatur,-3.23
-226000,Temperatur,-3.44
-225000,Temperatur,-3.44
-224000,Temperatur,-3.41
-223000,Temperatur,-3.25
-222000,Temperatur,-2.91
-221000,Temperatur,-2.52
-220000,Temperatur,-1.94
-219000,Temperatur,-1.6
-218000,Temperatur,-1.2
-217000,Temperatur,-0.98
-216000,Temperatur,-0.75
-215000,Temperatur,-0.68
-214000,Temperatur,-0.65
-213000,Temperatur,-0.73
-212000,Temperatur,-0.96
-211000,Temperatur,-1.08
-210000,Temperatur,-1.1
-209000,Temperatur,-1.24
-208000,Temperatur,-1.34
-207000,Temperatur,-1.4
-206000,Temperatur,-1.48
-205000,Temperatur,-1.56
-204000,Temperatur,-1.6
-203000,Temperatur,-1.54
-202000,Temperatur,-1.55
-201000,Temperatur,-1.62
-200000,Temperatur,-1.8
-199000,Temperatur,-1.96
-198000,Temperatur,-1.83
-197000,Temperatur,-2.02
-196000,Temperatur,-2.06
-195000,Temperatur,-2.2
-194000,Temperatur,-2.49
-193000,Temperatur,-2.96
-192000,Temperatur,-3.22
-191000,Temperatur,-3.03
-190000,Temperatur,-3.31
-189000,Temperatur,-3.38
-188000,Temperatur,-3.55
-187000,Temperatur,-3.63
-186000,Temperatur,-3.87
-185000,Temperatur,-4.17
-184000,Temperatur,-4.47
-183000,Temperatur,-4.68
-182000,Temperatur,-4.77
-181000,Temperatur,-4.84
-180000,Temperatur,-4.78
-179000,Temperatur,-4.67
-178000,Temperatur,-4.63
-177000,Temperatur,-4.59
-176000,Temperatur,-4.56
-175000,Temperatur,-4.6
-174000,Temperatur,-4.7
-173000,Temperatur,-4.83
-172000,Temperatur,-4.93
-171000,Temperatur,-4.86
-170000,Temperatur,-4.84
-169000,Temperatur,-4.84
-168000,Temperatur,-4.81
-167000,Temperatur,-4.96
-166000,Temperatur,-5.02
-165000,Temperatur,-5.1
-164000,Temperatur,-5.1
-163000,Temperatur,-5.12
-162000,Temperatur,-5.1
-161000,Temperatur,-5.06
-160000,Temperatur,-5.14
-159000,Temperatur,-5.2
-158000,Temperatur,-5.23
-157000,Temperatur,-5.26
-156000,Temperatur,-5.34
-155000,Temperatur,-5.41
-154000,Temperatur,-5.25
-153000,Temperatur,-5.27
-152000,Temperatur,-5.35
-151000,Temperatur,-5.48
-150000,Temperatur,-5.37
-149000,Temperatur,-5.42
-148000,Temperatur,-5.59
-147000,Temperatur,-5.67
-146000,Temperatur,-5.95
-145000,Temperatur,-5.93
-144000,Temperatur,-5.85
-143000,Temperatur,-5.71
-142000,Temperatur,-5.62
-141000,Temperatur,-5.47
-140000,Temperatur,-5.37
-139000,Temperatur,-5.38
-138000,Temperatur,-5.32
-137000,Temperatur,-5.26
-136000,Temperatur,-5.14
-135000,Temperatur,-4.96
-134000,Temperatur,-4.69
-133000,Temperatur,-4.24
-132000,Temperatur,-3.67
-131000,Temperatur,-3.05
-130000,Temperatur,-2.46
-129000,Temperatur,-1.87
-128000,Temperatur,-1.08
-127000,Temperatur,-0.43
-126000,Temperatur,0.13
-125000,Temperatur,0.61
-124000,Temperatur,1.05
-123000,Temperatur,1.36
-122000,Temperatur,1.65
-121000,Temperatur,1.86
-120000,Temperatur,1.85
-119000,Temperatur,1.71
-118000,Temperatur,1.41
-117000,Temperatur,0.96
-116000,Temperatur,0.54
-115000,Temperatur,0.14
-114000,Temperatur,-0.26
-113000,Temperatur,-0.61
-112000,Temperatur,-0.9
-111000,Temperatur,-1.25
-110000,Temperatur,-1.66
-109000,Temperatur,-2.06
-108000,Temperatur,-2.37
-107000,Temperatur,-2.35
-106000,Temperatur,-2.29
-105000,Temperatur,-2.2
-104000,Temperatur,-2.07
-103000,Temperatur,-1.96
-102000,Temperatur,-1.88
-101000,Temperatur,-1.73
-100000,Temperatur,-1.7
-99000,Temperatur,-1.63
-98000,Temperatur,-1.69
-97000,Temperatur,-1.74
-96000,Temperatur,-1.85
-95000,Temperatur,-2.02
-94000,Temperatur,-2.21
-93000,Temperatur,-2.38
-92000,Temperatur,-2.56
-91000,Temperatur,-2.74
-90000,Temperatur,-2.82
-89000,Temperatur,-2.9
-88000,Temperatur,-2.95
-87000,Temperatur,-2.96
-86000,Temperatur,-3.02
-85000,Temperatur,-2.99
-84000,Temperatur,-2.85
-83000,Temperatur,-2.7
-82000,Temperatur,-2.52
-81000,Temperatur,-2.48
-80000,Temperatur,-2.47
-79000,Temperatur,-2.45
-78000,Temperatur,-2.5
-77000,Temperatur,-2.61
-76000,Temperatur,-2.74
-75000,Temperatur,-2.92
-74000,Temperatur,-3.1
-73000,Temperatur,-3.43
-72000,Temperatur,-3.83
-71000,Temperatur,-4.14
-70000,Temperatur,-4.44
-69000,Temperatur,-4.75
-68000,Temperatur,-5.17
-67000,Temperatur,-5.47
-66000,Temperatur,-5.73
-65000,Temperatur,-5.96
-64000,Temperatur,-6.12
-63000,Temperatur,-6.25
-62000,Temperatur,-6.2
-61000,Temperatur,-6.15
-60000,Temperatur,-6.03
-59000,Temperatur,-5.93
-58000,Temperatur,-5.78
-57000,Temperatur,-5.6
-56000,Temperatur,-5.35
-55000,Temperatur,-5.21
-54000,Temperatur,-5.06
-53000,Temperatur,-5.01
-52000,Temperatur,-4.94
-51000,Temperatur,-4.94
-50000,Temperatur,-4.96
-49000,Temperatur,-5.08
-48000,Temperatur,-5.25
-47000,Temperatur,-5.34
-46000,Temperatur,-5.44
-45000,Temperatur,-5.44
-44000,Temperatur,-5.41
-43000,Temperatur,-5.49
-42000,Temperatur,-5.57
-41000,Temperatur,-5.76
-40000,Temperatur,-5.86
-39000,Temperatur,-5.94
-38000,Temperatur,-5.95
-37000,Temperatur,-5.89
-36000,Temperatur,-5.85
-35000,Temperatur,-5.76
-34000,Temperatur,-5.73
-33000,Temperatur,-5.72
-32000,Temperatur,-5.7
-31000,Temperatur,-5.72
-30000,Temperatur,-5.77
-29000,Temperatur,-5.88
-28000,Temperatur,-5.97
-27000,Temperatur,-6.05
-26000,Temperatur,-6.02
-25000,Temperatur,-6.07
-24000,Temperatur,-6.1
-23000,Temperatur,-6.26
-22000,Temperatur,-6.37
-21000,Temperatur,-6.39
-20000,Temperatur,-6.41
-19000,Temperatur,-6.39
-18000,Temperatur,-6.28
-17000,Temperatur,-6.07
-16000,Temperatur,-5.81
-15000,Temperatur,-5.41
-14000,Temperatur,-4.84
-13000,Temperatur,-4.25
-12000,Temperatur,-3.58
-11000,Temperatur,-2.85
-10000,Temperatur,-2.14
-9000,Temperatur,-1.47
-8000,Temperatur,-0.88
-7000,Temperatur,-0.47
-6000,Temperatur,-0.2
-5000,Temperatur,-0.08
-4000,Temperatur,0
-3000,Temperatur,-0.01
-2000,Temperatur,-0.05
-1000,Temperatur,-0.11
0,Temperatur,-0.23
1000,Temperatur,-0.31
2000,Temperatur,0.29
2018,Temperatur,0.6
-500k,Kohlendioxid,-3.03
-499000,Kohlendioxid,-3.13
-498000,Kohlendioxid,-3.19
-497000,Kohlendioxid,-3.09
-496000,Kohlendioxid,-2.81
-495000,Kohlendioxid,-2.54
-494000,Kohlendioxid,-2.45
-493000,Kohlendioxid,-2.34
-492000,Kohlendioxid,-2.32
-491000,Kohlendioxid,-2.25
-490000,Kohlendioxid,-1.85
-489000,Kohlendioxid,-1.67
-488000,Kohlendioxid,-1.93
-487000,Kohlendioxid,-1.16
-486000,Kohlendioxid,-2.21
-485000,Kohlendioxid,-2.92
-484000,Kohlendioxid,-2.87
-483000,Kohlendioxid,-2.93
-482000,Kohlendioxid,-3.03
-481000,Kohlendioxid,-3.02
-480000,Kohlendioxid,-3.4
-479000,Kohlendioxid,-3.78
-478000,Kohlendioxid,-3.82
-477000,Kohlendioxid,-4.13
-476000,Kohlendioxid,-2.82
-475000,Kohlendioxid,-2.34
-474000,Kohlendioxid,-2.63
-473000,Kohlendioxid,-2.87
-472000,Kohlendioxid,-2.7
-471000,Kohlendioxid,-2.02
-470000,Kohlendioxid,-1.73
-469000,Kohlendioxid,-2.08
-468000,Kohlendioxid,-3.23
-467000,Kohlendioxid,-4.46
-466000,Kohlendioxid,-5.43
-465000,Kohlendioxid,-5.57
-464000,Kohlendioxid,-5.66
-463000,Kohlendioxid,-5.59
-462000,Kohlendioxid,-5.35
-461000,Kohlendioxid,-5.16
-460000,Kohlendioxid,-5.24
-459000,Kohlendioxid,-5.92
-458000,Kohlendioxid,-6.33
-457000,Kohlendioxid,-6.66
-456000,Kohlendioxid,-6.86
-455000,Kohlendioxid,-6.54
-454000,Kohlendioxid,-6.1
-453000,Kohlendioxid,-5.63
-452000,Kohlendioxid,-5.28
-451000,Kohlendioxid,-5.61
-450000,Kohlendioxid,-6.39
-449000,Kohlendioxid,-6.67
-448000,Kohlendioxid,-6.44
-447000,Kohlendioxid,-6.07
-446000,Kohlendioxid,-5.78
-445000,Kohlendioxid,-5.54
-444000,Kohlendioxid,-5.85
-443000,Kohlendioxid,-5.85
-442000,Kohlendioxid,-5.45
-441000,Kohlendioxid,-5.46
-440000,Kohlendioxid,-5.75
-439000,Kohlendioxid,-5.92
-438000,Kohlendioxid,-6.04
-437000,Kohlendioxid,-5.94
-436000,Kohlendioxid,-5.83
-435000,Kohlendioxid,-5.87
-434000,Kohlendioxid,-5.84
-433000,Kohlendioxid,-5.95
-432000,Kohlendioxid,-5.46
-431000,Kohlendioxid,-5.15
-430000,Kohlendioxid,-5.18
-429000,Kohlendioxid,-4.77
-428000,Kohlendioxid,-3.51
-427000,Kohlendioxid,-4.04
-426000,Kohlendioxid,-2.54
-425000,Kohlendioxid,-1.24
-424000,Kohlendioxid,-0.69
-423000,Kohlendioxid,0.71
-422000,Kohlendioxid,0.45
-421000,Kohlendioxid,0.63
-420000,Kohlendioxid,0.36
-419000,Kohlendioxid,0.75
-418000,Kohlendioxid,0.83
-417000,Kohlendioxid,1.03
-416000,Kohlendioxid,0.94
-415000,Kohlendioxid,0.93
-414000,Kohlendioxid,1.04
-413000,Kohlendioxid,0.79
-412000,Kohlendioxid,0.17
-411000,Kohlendioxid,1.13
-410000,Kohlendioxid,1.55
-409000,Kohlendioxid,1.92
-408000,Kohlendioxid,1.61
-407000,Kohlendioxid,1.61
-406000,Kohlendioxid,2.08
-405000,Kohlendioxid,2.02
-404000,Kohlendioxid,1.59
-403000,Kohlendioxid,1.65
-402000,Kohlendioxid,1.26
-401000,Kohlendioxid,1.2
-400000,Kohlendioxid,1.89
-399000,Kohlendioxid,1.9
-398000,Kohlendioxid,1.5
-397000,Kohlendioxid,1.29
-396000,Kohlendioxid,1.19
-395000,Kohlendioxid,0.77
-394000,Kohlendioxid,0.35
-393000,Kohlendioxid,-0.07
-392000,Kohlendioxid,0.53
-391000,Kohlendioxid,0.18
-390000,Kohlendioxid,0.24
-389000,Kohlendioxid,-0.45
-388000,Kohlendioxid,-1.24
-387000,Kohlendioxid,-0.98
-386000,Kohlendioxid,-0.74
-385000,Kohlendioxid,-0.54
-384000,Kohlendioxid,-0.24
-383000,Kohlendioxid,-0.19
-382000,Kohlendioxid,-0.85
-381000,Kohlendioxid,-1.48
-380000,Kohlendioxid,-1.6
-379000,Kohlendioxid,-1.65
-378000,Kohlendioxid,-2.15
-377000,Kohlendioxid,-2.25
-376000,Kohlendioxid,-2.31
-375000,Kohlendioxid,-3.13
-374000,Kohlendioxid,-3.4
-373000,Kohlendioxid,-3.33
-372000,Kohlendioxid,-3.27
-371000,Kohlendioxid,-3.21
-370000,Kohlendioxid,-3.4
-369000,Kohlendioxid,-3.74
-368000,Kohlendioxid,-4.32
-367000,Kohlendioxid,-5.04
-366000,Kohlendioxid,-5.92
-365000,Kohlendioxid,-5.91
-364000,Kohlendioxid,-5.78
-363000,Kohlendioxid,-5.63
-362000,Kohlendioxid,-5.49
-361000,Kohlendioxid,-5.49
-360000,Kohlendioxid,-5.69
-359000,Kohlendioxid,-5.89
-358000,Kohlendioxid,-6.54
-357000,Kohlendioxid,-7.2
-356000,Kohlendioxid,-7.34
-355000,Kohlendioxid,-7.32
-354000,Kohlendioxid,-6.93
-353000,Kohlendioxid,-6.48
-352000,Kohlendioxid,-5.98
-351000,Kohlendioxid,-5.47
-350000,Kohlendioxid,-5.13
-349000,Kohlendioxid,-5.11
-348000,Kohlendioxid,-4.59
-347000,Kohlendioxid,-4.21
-346000,Kohlendioxid,-4.01
-345000,Kohlendioxid,-4.04
-344000,Kohlendioxid,-4.09
-343000,Kohlendioxid,-4.6
-342000,Kohlendioxid,-5.15
-341000,Kohlendioxid,-5.53
-340000,Kohlendioxid,-5.51
-339000,Kohlendioxid,-5.77
-338000,Kohlendioxid,-3.88
-337000,Kohlendioxid,-1.52
-336000,Kohlendioxid,-2.3
-335000,Kohlendioxid,-2.41
-334000,Kohlendioxid,-2.03
-333000,Kohlendioxid,0.18
-332000,Kohlendioxid,2.04
-331000,Kohlendioxid,3.23
-330000,Kohlendioxid,1.84
-329000,Kohlendioxid,0.92
-328000,Kohlendioxid,0.58
-327000,Kohlendioxid,0.57
-326000,Kohlendioxid,1
-325000,Kohlendioxid,0.65
-324000,Kohlendioxid,0.16
-323000,Kohlendioxid,0.27
-322000,Kohlendioxid,-0.26
-321000,Kohlendioxid,-0.26
-320000,Kohlendioxid,-0.59
-319000,Kohlendioxid,-1.05
-318000,Kohlendioxid,-1.03
-317000,Kohlendioxid,-1.92
-316000,Kohlendioxid,-2
-315000,Kohlendioxid,-1.14
-314000,Kohlendioxid,-0.08
-313000,Kohlendioxid,-0.69
-312000,Kohlendioxid,-0.75
-311000,Kohlendioxid,-1.68
-310000,Kohlendioxid,-2.27
-309000,Kohlendioxid,-2.44
-308000,Kohlendioxid,-3.04
-307000,Kohlendioxid,-3.41
-306000,Kohlendioxid,-3.48
-305000,Kohlendioxid,-2.51
-304000,Kohlendioxid,-1.51
-303000,Kohlendioxid,-1.24
-302000,Kohlendioxid,-2.14
-301000,Kohlendioxid,-2.3
-300000,Kohlendioxid,-2.48
-299000,Kohlendioxid,-2.43
-298000,Kohlendioxid,-2.87
-297000,Kohlendioxid,-3.53
-296000,Kohlendioxid,-4.35
-295000,Kohlendioxid,-4.57
-294000,Kohlendioxid,-4.76
-293000,Kohlendioxid,-4.78
-292000,Kohlendioxid,-5.24
-291000,Kohlendioxid,-5.4
-290000,Kohlendioxid,-4.88
-289000,Kohlendioxid,-4.17
-288000,Kohlendioxid,-2.72
-287000,Kohlendioxid,-2.91
-286000,Kohlendioxid,-3.07
-285000,Kohlendioxid,-3.06
-284000,Kohlendioxid,-3.45
-283000,Kohlendioxid,-3.25
-282000,Kohlendioxid,-3.06
-281000,Kohlendioxid,-3.32
-280000,Kohlendioxid,-3.68
-279000,Kohlendioxid,-4.19
-278000,Kohlendioxid,-4.68
-277000,Kohlendioxid,-5.19
-276000,Kohlendioxid,-5.66
-275000,Kohlendioxid,-6.13
-274000,Kohlendioxid,-6.46
-273000,Kohlendioxid,-6.31
-272000,Kohlendioxid,-6.57
-271000,Kohlendioxid,-6.7
-270000,Kohlendioxid,-7.1
-269000,Kohlendioxid,-7.05
-268000,Kohlendioxid,-6.23
-267000,Kohlendioxid,-6.69
-266000,Kohlendioxid,-7.17
-265000,Kohlendioxid,-6.11
-264000,Kohlendioxid,-5.52
-263000,Kohlendioxid,-4.37
-262000,Kohlendioxid,-3.79
-261000,Kohlendioxid,-4.59
-260000,Kohlendioxid,-5.19
-259000,Kohlendioxid,-5.45
-258000,Kohlendioxid,-5.22
-257000,Kohlendioxid,-5.53
-256000,Kohlendioxid,-5.63
-255000,Kohlendioxid,-5.66
-254000,Kohlendioxid,-5.94
-253000,Kohlendioxid,-6.2
-252000,Kohlendioxid,-6.38
-251000,Kohlendioxid,-6.34
-250k,Kohlendioxid,-6.43
-249000,Kohlendioxid,-4.77
-248000,Kohlendioxid,-5.88
-247000,Kohlendioxid,-5.32
-246000,Kohlendioxid,-4.76
-245000,Kohlendioxid,-4.46
-244000,Kohlendioxid,-4.26
-243000,Kohlendioxid,-3.26
-242000,Kohlendioxid,-1.5
-241000,Kohlendioxid,0.32
-240000,Kohlendioxid,1.37
-239000,Kohlendioxid,-0.33
-238000,Kohlendioxid,-1.01
-237000,Kohlendioxid,-1.65
-236000,Kohlendioxid,-2.21
-235000,Kohlendioxid,-1.66
-234000,Kohlendioxid,-1.8
-233000,Kohlendioxid,-1.57
-232000,Kohlendioxid,-1.78
-231000,Kohlendioxid,-1.88
-230000,Kohlendioxid,-1.97
-229000,Kohlendioxid,-2.18
-228000,Kohlendioxid,-2.85
-227000,Kohlendioxid,-3.14
-226000,Kohlendioxid,-3.6
-225000,Kohlendioxid,-2.83
-224000,Kohlendioxid,-2.64
-223000,Kohlendioxid,-4.46
-222000,Kohlendioxid,-5.66
-221000,Kohlendioxid,-5.55
-220000,Kohlendioxid,-5.45
-219000,Kohlendioxid,-5.21
-218000,Kohlendioxid,-5.23
-217000,Kohlendioxid,-4.51
-216000,Kohlendioxid,-4.15
-215000,Kohlendioxid,-2.9
-214000,Kohlendioxid,-1.96
-213000,Kohlendioxid,-1.29
-212000,Kohlendioxid,-1.53
-211000,Kohlendioxid,-2.11
-210000,Kohlendioxid,-1.24
-209000,Kohlendioxid,-1.78
-208000,Kohlendioxid,-1.57
-207000,Kohlendioxid,-1.16
-206000,Kohlendioxid,-1.81
-205000,Kohlendioxid,-2.7
-204000,Kohlendioxid,-2.38
-203000,Kohlendioxid,-3.19
-202000,Kohlendioxid,-3.32
-201000,Kohlendioxid,-2.96
-200000,Kohlendioxid,-1.67
-199000,Kohlendioxid,-1.62
-198000,Kohlendioxid,-2.27
-197000,Kohlendioxid,-1.17
-196000,Kohlendioxid,-1.45
-195000,Kohlendioxid,-1.73
-194000,Kohlendioxid,-2.01
-193000,Kohlendioxid,-3.52
-192000,Kohlendioxid,-3.91
-191000,Kohlendioxid,-3.53
-190000,Kohlendioxid,-3.79
-189000,Kohlendioxid,-4.1
-188000,Kohlendioxid,-4.22
-187000,Kohlendioxid,-3.86
-186000,Kohlendioxid,-3.02
-185000,Kohlendioxid,-3.03
-184000,Kohlendioxid,-3.75
-183000,Kohlendioxid,-4.73
-182000,Kohlendioxid,-5.17
-181000,Kohlendioxid,-5.44
-180000,Kohlendioxid,-5.7
-179000,Kohlendioxid,-5.88
-178000,Kohlendioxid,-6.05
-177000,Kohlendioxid,-5.85
-176000,Kohlendioxid,-4.41
-175000,Kohlendioxid,-4.8
-174000,Kohlendioxid,-5.09
-173000,Kohlendioxid,-5.58
-172000,Kohlendioxid,-6.46
-171000,Kohlendioxid,-6.99
-170000,Kohlendioxid,-6.68
-169000,Kohlendioxid,-6.34
-168000,Kohlendioxid,-6.26
-167000,Kohlendioxid,-6.22
-166000,Kohlendioxid,-6.21
-165000,Kohlendioxid,-6.22
-164000,Kohlendioxid,-6.26
-163000,Kohlendioxid,-6.3
-162000,Kohlendioxid,-7.12
-161000,Kohlendioxid,-7.24
-160000,Kohlendioxid,-6.86
-159000,Kohlendioxid,-6.6
-158000,Kohlendioxid,-6.33
-157000,Kohlendioxid,-5.85
-156000,Kohlendioxid,-6.28
-155000,Kohlendioxid,-6.7
-154000,Kohlendioxid,-7.13
-153000,Kohlendioxid,-7.22
-152000,Kohlendioxid,-6.86
-151000,Kohlendioxid,-6.49
-150000,Kohlendioxid,-6.13
-149000,Kohlendioxid,-6.29
-148000,Kohlendioxid,-7.04
-147000,Kohlendioxid,-5.85
-146000,Kohlendioxid,-5.86
-145000,Kohlendioxid,-6.03
-144000,Kohlendioxid,-6.2
-143000,Kohlendioxid,-6.37
-142000,Kohlendioxid,-6.56
-141000,Kohlendioxid,-6.74
-140000,Kohlendioxid,-6.86
-139000,Kohlendioxid,-6.35
-138000,Kohlendioxid,-6.35
-137000,Kohlendioxid,-6.79
-136000,Kohlendioxid,-6.56
-135000,Kohlendioxid,-6.19
-134000,Kohlendioxid,-5.89
-133000,Kohlendioxid,-5.57
-132000,Kohlendioxid,-5.12
-131000,Kohlendioxid,-3.74
-130000,Kohlendioxid,-3.41
-129000,Kohlendioxid,-1.41
-128000,Kohlendioxid,-0.58
-127000,Kohlendioxid,1.32
-126000,Kohlendioxid,1.16
-125000,Kohlendioxid,-0.06
-124000,Kohlendioxid,1.14
-123000,Kohlendioxid,1
-122000,Kohlendioxid,0.7
-121000,Kohlendioxid,1.19
-120000,Kohlendioxid,1
-119000,Kohlendioxid,1.25
-118000,Kohlendioxid,0.58
-117000,Kohlendioxid,0.95
-116000,Kohlendioxid,0.56
-115000,Kohlendioxid,0.11
-114000,Kohlendioxid,0.35
-113000,Kohlendioxid,0.99
-112000,Kohlendioxid,-0.08
-111000,Kohlendioxid,0.1
-110000,Kohlendioxid,-0.56
-109000,Kohlendioxid,-0.84
-108000,Kohlendioxid,-1.1
-107000,Kohlendioxid,-1.41
-106000,Kohlendioxid,-1.92
-105000,Kohlendioxid,-2.61
-104000,Kohlendioxid,-2.98
-103000,Kohlendioxid,-2.66
-102000,Kohlendioxid,-3.01
-101000,Kohlendioxid,-3.08
-100000,Kohlendioxid,-2.59
-99000,Kohlendioxid,-3
-98000,Kohlendioxid,-3.5
-97000,Kohlendioxid,-3.45
-96000,Kohlendioxid,-3.35
-95000,Kohlendioxid,-3.24
-94000,Kohlendioxid,-3.13
-93000,Kohlendioxid,-3.03
-92000,Kohlendioxid,-3.01
-91000,Kohlendioxid,-3.12
-90000,Kohlendioxid,-3.24
-89000,Kohlendioxid,-3.44
-88000,Kohlendioxid,-3.96
-87000,Kohlendioxid,-4.58
-86000,Kohlendioxid,-5.22
-85000,Kohlendioxid,-4.77
-84000,Kohlendioxid,-4.44
-83000,Kohlendioxid,-4.56
-82000,Kohlendioxid,-3.26
-81000,Kohlendioxid,-2.35
-80000,Kohlendioxid,-2.34
-79000,Kohlendioxid,-2.88
-78000,Kohlendioxid,-3.3
-77000,Kohlendioxid,-3.66
-76000,Kohlendioxid,-4.03
-75000,Kohlendioxid,-4.32
-74000,Kohlendioxid,-4.02
-73000,Kohlendioxid,-3.74
-72000,Kohlendioxid,-3.44
-71000,Kohlendioxid,-3.25
-70000,Kohlendioxid,-3.34
-69000,Kohlendioxid,-3.46
-68000,Kohlendioxid,-4.07
-67000,Kohlendioxid,-4.67
-66000,Kohlendioxid,-5.27
-65000,Kohlendioxid,-5.88
-64000,Kohlendioxid,-6.48
-63000,Kohlendioxid,-6.82
-62000,Kohlendioxid,-6.64
-61000,Kohlendioxid,-6.47
-60000,Kohlendioxid,-6.2
-59000,Kohlendioxid,-5.92
-58000,Kohlendioxid,-5.65
-57000,Kohlendioxid,-5.37
-56000,Kohlendioxid,-5.1
-55000,Kohlendioxid,-4.02
-54000,Kohlendioxid,-4.66
-53000,Kohlendioxid,-5.29
-52000,Kohlendioxid,-5.92
-51000,Kohlendioxid,-6.55
-50000,Kohlendioxid,-6.3
-49000,Kohlendioxid,-4.91
-48000,Kohlendioxid,-4.9
-47000,Kohlendioxid,-6.86
-46000,Kohlendioxid,-7.05
-45000,Kohlendioxid,-6.83
-44000,Kohlendioxid,-6.33
-43000,Kohlendioxid,-5.85
-42000,Kohlendioxid,-5.35
-41000,Kohlendioxid,-5.14
-40000,Kohlendioxid,-5.14
-39000,Kohlendioxid,-5.14
-38000,Kohlendioxid,-5.14
-37000,Kohlendioxid,-5.14
-36000,Kohlendioxid,-5.14
-35000,Kohlendioxid,-5.21
-34000,Kohlendioxid,-5.35
-33000,Kohlendioxid,-5.52
-32000,Kohlendioxid,-5.77
-31000,Kohlendioxid,-6.03
-30000,Kohlendioxid,-6.29
-29000,Kohlendioxid,-6.55
-28000,Kohlendioxid,-6.81
-27000,Kohlendioxid,-7.08
-26000,Kohlendioxid,-6.99
-25000,Kohlendioxid,-6.89
-24000,Kohlendioxid,-6.8
-23000,Kohlendioxid,-6.87
-22000,Kohlendioxid,-6.94
-21000,Kohlendioxid,-7.02
-20000,Kohlendioxid,-7.43
-19000,Kohlendioxid,-7.27
-18000,Kohlendioxid,-7.11
-17000,Kohlendioxid,-7.11
-16000,Kohlendioxid,-7.03
-15000,Kohlendioxid,-6.49
-14000,Kohlendioxid,-4.88
-13000,Kohlendioxid,-3.63
-12000,Kohlendioxid,-2.3
-11000,Kohlendioxid,-2.46
-10000,Kohlendioxid,-1.59
-9000,Kohlendioxid,0.09
-8000,Kohlendioxid,0.2
-7000,Kohlendioxid,0.17
-6000,Kohlendioxid,-0.28
-5000,Kohlendioxid,-0.03
-4000,Kohlendioxid,0.08
-3000,Kohlendioxid,0.58
-2000,Kohlendioxid,0.81
-1000,Kohlendioxid,1.13
0,Kohlendioxid,1.31
1000,Kohlendioxid,1.28
2000,Kohlendioxid,10.1
2018,Kohlendioxid,13.81
```

Quelle: [Snyder (2016)](https://www.nature.com/articles/nature19798#supplementary-information), [MetOffice](https://www.metoffice.gov.uk/hadobs/hadcrut4/data/current/download.html), [co2levels.org](https://www.co2levels.org/#sources). Die CO<sub>2</sub>-Kurve wurde auf der vertikalen Achse an die Temperaturkurve angeglichen.

<hr /></section>

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesqueeu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo,fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut,imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputateeleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac,enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellusviverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiamultricies nisi vel augue.

<section><h6>CHART</h6>

```
{
  "type": "Line",
  "y": "label"
}
```

### Globaler Temperaturanstieg seit der Industrialisierung

Abweichung vom langjährigen Durchschnitt 1951–1980

```
year,value
1880,-0.11
1881,-0.14
1882,-0.18
1883,-0.21
1884,-0.24
1885,-0.26
1886,-0.27
1887,-0.27
1888,-0.27
1889,-0.26
1890,-0.25
1891,-0.26
1892,-0.27
1893,-0.26
1894,-0.24
1895,-0.22
1896,-0.21
1897,-0.18
1898,-0.17
1899,-0.18
1900,-0.2
1901,-0.24
1902,-0.26
1903,-0.29
1904,-0.32
1905,-0.34
1906,-0.36
1907,-0.38
1908,-0.39
1909,-0.4
1910,-0.41
1911,-0.38
1912,-0.34
1913,-0.31
1914,-0.3
1915,-0.29
1916,-0.28
1917,-0.28
1918,-0.28
1919,-0.28
1920,-0.26
1921,-0.25
1922,-0.24
1923,-0.23
1924,-0.22
1925,-0.21
1926,-0.21
1927,-0.2
1928,-0.18
1929,-0.18
1930,-0.18
1931,-0.18
1932,-0.18
1933,-0.17
1934,-0.16
1935,-0.15
1936,-0.12
1937,-0.08
1938,-0.03
1939,0.02
1940,0.05
1941,0.08
1942,0.1
1943,0.09
1944,0.07
1945,0.04
1946,0.0
1947,-0.04
1948,-0.07
1949,-0.08
1950,-0.08
1951,-0.07
1952,-0.07
1953,-0.08
1954,-0.07
1955,-0.06
1956,-0.05
1957,-0.04
1958,-0.01
1959,0.02
1960,0.03
1961,0.02
1962,-0.0
1963,-0.02
1964,-0.03
1965,-0.04
1966,-0.05
1967,-0.04
1968,-0.03
1969,-0.01
1970,-0.0
1971,0.0
1972,0.0
1973,-0.01
1974,-0.0
1975,0.02
1976,0.03
1977,0.07
1978,0.12
1979,0.16
1980,0.2
1981,0.21
1982,0.22
1983,0.21
1984,0.21
1985,0.23
1986,0.25
1987,0.28
1988,0.31
1989,0.34
1990,0.34
1991,0.33
1992,0.33
1993,0.33
1994,0.34
1995,0.37
1996,0.4
1997,0.43
1998,0.45
1999,0.47
2000,0.5
2001,0.52
2002,0.54
2003,0.57
2004,0.6
2005,0.6
2006,0.61
2007,0.61
2008,0.62
2009,0.62
2010,0.62
2011,0.64
2012,0.67
2013,0.71
2014,0.76
2015,0.8
2016,0.85
2017,0.89
2018,0.93
```

Quelle: [NASA](https://climate.nasa.gov/vital-signs/global-temperature/)

<hr /></section>

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesqueeu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo,fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut,imperdiet a, venenatis vitae, justo. 

<section><h6>ARTICLECOLLECTION</h6>

```
{
  "membersOnly": true,
  "unauthorizedText": ""
}
```

## Die lange Sicht auf die globale Erwärmung

<section><h6>TEASERGROUP</h6>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-ein-120-000-jahre-rekord?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-auf-langer-sicht?autoSlug",
  "titleSize": "standard",
  "id": "O4b1BvaN-",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Auf lange Sicht

# Höchste Temperatur seit 120’000 Jahren gemessen!

## 

#### Nein, diese Schlagzeile ist kein Witz: Wir analysieren Temperatur­daten aus den vergangenen Jahrtausenden – und zeigen, wie der Mensch gerade die nächste Eiszeit verhindert.

Von [Arian Bastani](/~5d99ec6e-cb7d-4b27-8bf9-375b61e7ea7e), 03.06.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-klima-temperaturen?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-auf-langer-sicht?autoSlug",
  "titleSize": "standard",
  "id": "nuFpFoL1XV",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Auf lange Sicht

# Wie El Niño und Vulkane das Klima beeinflussen

## 

#### Warum die Erdtemperatur nicht nur steigt, sondern auch schwankt: zwei Betrachtungen über 150 und 1500 Jahre.

Von [Arian Bastani](/~5d99ec6e-cb7d-4b27-8bf9-375b61e7ea7e "Arian Bastani"), 06.05.2019

<hr /></section>

<hr /></section>

<hr /></section>

Nullam dictum felis eu pede mollis pretium.Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputateeleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac,enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellusviverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiamultricies nisi vel augue.

<section><h6>DYNAMIC_COMPONENT</h6>

```
{
  "autoHtml": false,
  "props": {
    "item": {
      "color": "#FCFDDB",
      "header": "Serie Wissenschaftsgeschichte des Klimawandels",
      "date": "Von Arian Bastiani, 4.12. – 27.17.2018",
      "url": "https://www.republik.ch/2019/03/19/das-versagen-der-eth",
      "title": "Geheimnisvolle Strahlen",
      "textPosition": "topleft",
      "image": "https://cdn.republik.space/s3/republik-assets/github/republik/article-klima-forschungsgeschichte-teil-1/images/2b0b82cc16d0baaf0491b5bf1e6e70c72cb435d3.jpeg",
      "lead": "Wie die Klimaforschung den Weg in die Politik fand – und dort von mächtigen Gegnern bekämpft wurde. Ein Serie in vier Teilen."
    }
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/banner.js?v7",
  "size": "breakout"
}
```

<hr /></section>

## Der Schweiz, vermeintlicher Musterknabe

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesqueeu, pretium quis, sem. AuCO₂-Ausstoss pro Kopf der Schweiz und ihren Nachbarländern

<section><h6>CHART</h6>

```
{
  "type": "TimeBar",
  "y": "value",
  "color": "label",
  "xTicks": [
    1960,
    1970,
    1980,
    1990,
    2000,
    2010,
    2017
  ],
  "unit": "Tonnen CO2"
}
```

### Auf und ab

Jährlicher CO₂-Ausstoss pro Einwohner in der Schweiz und den Nachbarländern

```
year,label,value
1960,Schweiz,3.6810
1960,Deutschland,11.0871
1960,Frankreich,5.9165
1960,Italien,2.1954
1960,Österreich,4.3538
1961,Schweiz,3.7745
1961,Deutschland,11.2926
1961,Frankreich,6.0548
1961,Italien,2.4828
1961,Österreich,4.4752
1962,Schweiz,4.3830
1962,Deutschland,11.8563
1962,Frankreich,6.3425
1962,Italien,2.8969
1962,Österreich,4.7318
1963,Schweiz,5.1737
1963,Deutschland,12.5932
1963,Frankreich,6.9949
1963,Italien,3.2327
1963,Österreich,5.1276
1964,Schweiz,4.9090
1964,Deutschland,12.8035
1964,Frankreich,7.1388
1964,Italien,3.4239
1964,Österreich,5.3605
1965,Schweiz,5.2023
1965,Deutschland,12.5905
1965,Frankreich,7.1930
1965,Italien,3.6639
1965,Österreich,5.2211
1966,Schweiz,5.3213
1966,Deutschland,12.3857
1966,Frankreich,7.0349
1966,Italien,4.1059
1966,Österreich,5.3329
1967,Schweiz,5.4274
1967,Deutschland,12.1034
1967,Frankreich,7.4806
1967,Italien,4.4606
1967,Österreich,5.3961
1968,Schweiz,5.9411
1968,Deutschland,12.6512
1968,Frankreich,7.6825
1968,Italien,4.7146
1968,Österreich,5.6854
1969,Schweiz,6.2222
1969,Deutschland,13.4433
1969,Frankreich,8.1987
1969,Italien,5.0676
1969,Österreich,5.9682
1970,Schweiz,6.5233
1970,Deutschland,13.0582
1970,Frankreich,8.6466
1970,Italien,5.5314
1970,Österreich,6.7363
1971,Schweiz,6.7326
1971,Deutschland,13.1651
1971,Frankreich,9.0328
1971,Italien,5.7655
1971,Österreich,6.8963
1972,Schweiz,6.8445
1972,Deutschland,13.1997
1972,Frankreich,9.3083
1972,Italien,6.0426
1972,Österreich,7.3962
1973,Schweiz,7.3204
1973,Deutschland,13.7546
1973,Frankreich,9.9130
1973,Italien,6.4618
1973,Österreich,7.8895
1974,Schweiz,6.5331
1974,Deutschland,13.4663
1974,Frankreich,9.4977
1974,Italien,6.5111
1974,Österreich,7.5128
1975,Schweiz,6.1438
1975,Deutschland,12.7106
1975,Frankreich,8.4475
1975,Italien,6.1639
1975,Österreich,7.0982
1976,Schweiz,6.3628
1976,Deutschland,13.8441
1976,Frankreich,9.5070
1976,Italien,6.5786
1976,Österreich,7.6176
1977,Schweiz,6.4716
1977,Deutschland,13.3746
1977,Frankreich,9.0064
1977,Italien,6.3464
1977,Österreich,7.3324
1978,Schweiz,6.6708
1978,Deutschland,13.7312
1978,Frankreich,9.4388
1978,Italien,6.6232
1978,Österreich,7.5025
1979,Schweiz,6.3211
1979,Deutschland,14.2487
1979,Frankreich,9.8451
1979,Italien,6.8494
1979,Österreich,8.0497
1980,Schweiz,6.4233
1980,Deutschland,14.0492
1980,Frankreich,9.3618
1980,Italien,6.8493
1980,Österreich,6.8367
1981,Schweiz,6.1451
1981,Deutschland,13.4208
1981,Frankreich,8.3910
1981,Italien,6.6335
1981,Österreich,7.3422
1982,Schweiz,5.7691
1982,Deutschland,13.0314
1982,Frankreich,8.0299
1982,Italien,6.4686
1982,Österreich,7.0461
1983,Schweiz,6.2759
1983,Deutschland,13.0042
1983,Frankreich,7.7338
1983,Italien,6.3057
1983,Österreich,6.7958
1984,Schweiz,6.0978
1984,Deutschland,13.2970
1984,Frankreich,7.3917
1984,Italien,6.4035
1984,Österreich,7.1267
1985,Schweiz,6.1615
1985,Deutschland,13.4347
1985,Frankreich,7.2649
1985,Italien,6.4720
1985,Österreich,7.1396
1986,Schweiz,6.5052
1986,Deutschland,13.4571
1986,Frankreich,6.9549
1986,Italien,6.3648
1986,Österreich,7.0461
1987,Schweiz,6.1550
1987,Deutschland,13.2272
1987,Frankreich,6.7773
1987,Italien,6.6580
1987,Österreich,7.5105
1988,Schweiz,6.1868
1988,Deutschland,13.1329
1988,Frankreich,6.6490
1988,Italien,6.7591
1988,Österreich,6.9121
1989,Schweiz,5.9551
1989,Deutschland,12.8659
1989,Frankreich,6.9347
1989,Italien,7.0867
1989,Österreich,6.9859
1990,Schweiz,6.6161
1990,Deutschland,13.3091
1990,Frankreich,7.0768
1990,Italien,7.7011
1990,Österreich,8.0648
1991,Schweiz,6.8446
1991,Deutschland,12.7566
1991,Frankreich,7.4889
1991,Italien,7.7004
1991,Österreich,8.4784
1992,Schweiz,6.7517
1992,Deutschland,12.0769
1992,Frankreich,7.2777
1992,Italien,7.6800
1992,Österreich,7.7170
1993,Schweiz,6.3272
1993,Deutschland,11.8852
1993,Frankreich,6.9036
1993,Italien,7.5420
1993,Österreich,7.7024
1994,Schweiz,6.1309
1994,Deutschland,11.6199
1994,Frankreich,6.7838
1994,Italien,7.4320
1994,Österreich,7.6996
1995,Schweiz,6.1856
1995,Deutschland,11.5716
1995,Frankreich,6.8776
1995,Italien,7.8941
1995,Österreich,8.0357
1996,Schweiz,6.2452
1996,Deutschland,11.7919
1996,Frankreich,7.1144
1996,Italien,7.7680
1996,Österreich,8.4404
1997,Schweiz,6.0683
1997,Deutschland,11.4399
1997,Frankreich,6.9678
1997,Italien,7.8599
1997,Österreich,8.3971
1998,Schweiz,6.2701
1998,Deutschland,11.3425
1998,Frankreich,7.2803
1998,Italien,8.0527
1998,Österreich,8.3390
1999,Schweiz,6.2257
1999,Deutschland,11.0072
1999,Frankreich,7.1764
1999,Italien,8.1252
1999,Österreich,8.1506
2000,Schweiz,6.0849
2000,Deutschland,11.0564
2000,Frankreich,7.0570
2000,Italien,8.2167
2000,Österreich,8.2116
2001,Schweiz,6.2582
2001,Deutschland,11.2524
2001,Frankreich,7.1086
2001,Italien,8.2809
2001,Österreich,8.6927
2002,Schweiz,5.9993
2002,Deutschland,11.0395
2002,Frankreich,6.9891
2002,Italien,8.2646
2002,Österreich,8.8693
2003,Schweiz,6.1224
2003,Deutschland,11.0418
2003,Frankreich,7.0686
2003,Italien,8.4524
2003,Österreich,9.5114
2004,Schweiz,6.1558
2004,Deutschland,10.8669
2004,Frankreich,7.0447
2004,Italien,8.4713
2004,Österreich,9.4991
2005,Schweiz,6.1779
2005,Deutschland,10.6185
2005,Frankreich,7.0654
2005,Italien,8.4211
2005,Österreich,9.6160
2006,Schweiz,6.0638
2006,Deutschland,10.7768
2006,Frankreich,6.8531
2006,Italien,8.2896
2006,Österreich,9.2566
2007,Schweiz,5.7352
2007,Deutschland,10.4752
2007,Frankreich,6.6638
2007,Italien,8.1009
2007,Österreich,8.9069
2008,Schweiz,5.8470
2008,Deutschland,10.5314
2008,Frankreich,6.5264
2008,Italien,7.8663
2008,Österreich,8.8513
2009,Schweiz,5.6258
2009,Deutschland,9.7568
2009,Frankreich,6.1726
2009,Italien,6.9738
2009,Österreich,8.0625
2010,Schweiz,5.7514
2010,Deutschland,10.3058
2010,Frankreich,6.3132
2010,Italien,7.1133
2010,Österreich,8.6068
2011,Schweiz,5.1674
2011,Deutschland,10.0181
2011,Frankreich,5.8852
2011,Italien,6.9182
2011,Österreich,8.2880
2012,Schweiz,5.2605
2012,Deutschland,10.0559
2012,Frankreich,5.8786
2012,Italien,6.5623
2012,Österreich,7.9438
2013,Schweiz,5.3099
2013,Deutschland,10.2460
2013,Frankreich,5.8551
2013,Italien,6.0904
2013,Österreich,7.9276
2014,Schweiz,4.7679
2014,Deutschland,9.7391
2014,Frankreich,5.3524
2014,Italien,5.8483
2014,Österreich,7.4426
2015,Schweiz,4.6562
2015,Deutschland,9.7552
2015,Frankreich,5.4015
2015,Italien,5.9741
2015,Österreich,7.6860
2016,Schweiz,4.6663
2016,Deutschland,9.7877
2016,Frankreich,5.4095
2016,Italien,5.8947
2016,Österreich,7.7366
2017,Schweiz,4.7279
2017,Deutschland,9.7349
2017,Frankreich,5.4833
2017,Italien,5.9881
2017,Österreich,8.0067
```

Quelle: Carbon Atlas. Berücksichtigt sind die Emissionen im Inland, ohne den Flugverkehr und die grauen Emissionen aus importierten Produkten.

<hr /></section>

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesqueeu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo,fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut,imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputateeleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac,enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellusviverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiamultricies nisi vel augue. 

<section><h6>CHART</h6>

```
{
  "type": "Line",
  "color": "category",
  "x": "date",
  "numberFormat": ".1f",
  "yNice": 0,
  "yTicks": [
    0,
    20,
    40,
    60
  ],
  "colorRange": [
    "#444444",
    "#ff7f0e",
    "#d62728",
    "#e377c2",
    "#9467bd",
    "#1f77b4",
    "#17becf",
    "#bcbd22",
    "#2ca02c"
  ],
  "colorSort": "none",
  "stroke": "datum.category[0] == '-'",
  "xTicks": [
    1990,
    2016,
    2041,
    2050,
    2066,
    2080
  ],
  "endLabel": false,
  "size": "breakout",
  "labelFilter": "false",
  "colorLegendValues": [
    "bisherige Entwicklung",
    "-0.5%",
    "-1%",
    "-1.5%",
    "-2%",
    "-2.5%",
    "-3%",
    "-3.5%",
    "-4% pro Jahr"
  ],
  "unit": "Millionen Tonnen CO2-Äquivalente"
}
```

### Minus 3 Prozent sind nötig für das Ziel

Treibhausgasausstoss der Schweiz: bisherige Entwicklung und mögliche Absenkpfade

```
date,category,value
1990,bisherige Entwicklung,53.59
1991,bisherige Entwicklung,55.44
1992,bisherige Entwicklung,55.18
1993,bisherige Entwicklung,52.51
1994,bisherige Entwicklung,51.49
1995,bisherige Entwicklung,52.33
1996,bisherige Entwicklung,53.01
1997,bisherige Entwicklung,51.78
1998,bisherige Entwicklung,53.39
1999,bisherige Entwicklung,53.13
2000,bisherige Entwicklung,52.36
2001,bisherige Entwicklung,53.94
2002,bisherige Entwicklung,52.34
2003,bisherige Entwicklung,53.5
2004,bisherige Entwicklung,54.13
2005,bisherige Entwicklung,54.73
2006,bisherige Entwicklung,54.41
2007,bisherige Entwicklung,52.48
2008,bisherige Entwicklung,54.01
2009,bisherige Entwicklung,52.66
2010,bisherige Entwicklung,54.24
2011,bisherige Entwicklung,50.19
2012,bisherige Entwicklung,51.53
2013,bisherige Entwicklung,52.38
2014,bisherige Entwicklung,48.46
2015,bisherige Entwicklung,47.91
2016,bisherige Entwicklung,48.29
2016,-0.5%,48.29
2016,-1%,48.29
2016,-1.5%,48.29
2016,-2%,48.29
2016,-2.5%,48.29
2016,-3%,48.29
2016,-3.5%,48.29
2016,-4% pro Jahr,48.29
2017,-0.5%,48.04855
2017,-1%,47.8071
2017,-1.5%,47.56565
2017,-2%,47.3242
2017,-2.5%,47.08275
2017,-3%,46.8413
2017,-3.5%,46.599849999999996
2017,-4% pro Jahr,46.358399999999996
2018,-0.5%,47.8071
2018,-1%,47.3242
2018,-1.5%,46.8413
2018,-2%,46.358399999999996
2018,-2.5%,45.875499999999995
2018,-3%,45.392599999999995
2018,-3.5%,44.909699999999994
2018,-4% pro Jahr,44.42679999999999
2019,-0.5%,47.56565
2019,-1%,46.8413
2019,-1.5%,46.116949999999996
2019,-2%,45.392599999999995
2019,-2.5%,44.66824999999999
2019,-3%,43.94389999999999
2019,-3.5%,43.21954999999999
2019,-4% pro Jahr,42.49519999999999
2020,-0.5%,47.3242
2020,-1%,46.358399999999996
2020,-1.5%,45.392599999999995
2020,-2%,44.42679999999999
2020,-2.5%,43.46099999999999
2020,-3%,42.49519999999999
2020,-3.5%,41.52939999999999
2020,-4% pro Jahr,40.56359999999999
2021,-0.5%,47.08275
2021,-1%,45.875499999999995
2021,-1.5%,44.66824999999999
2021,-2%,43.46099999999999
2021,-2.5%,42.25374999999999
2021,-3%,41.04649999999999
2021,-3.5%,39.839249999999986
2021,-4% pro Jahr,38.631999999999984
2022,-0.5%,46.8413
2022,-1%,45.392599999999995
2022,-1.5%,43.94389999999999
2022,-2%,42.49519999999999
2022,-2.5%,41.04649999999999
2022,-3%,39.597799999999985
2022,-3.5%,38.14909999999998
2022,-4% pro Jahr,36.70039999999998
2023,-0.5%,46.599849999999996
2023,-1%,44.909699999999994
2023,-1.5%,43.21954999999999
2023,-2%,41.52939999999999
2023,-2.5%,39.839249999999986
2023,-3%,38.14909999999998
2023,-3.5%,36.45894999999998
2023,-4% pro Jahr,34.76879999999998
2024,-0.5%,46.358399999999996
2024,-1%,44.42679999999999
2024,-1.5%,42.49519999999999
2024,-2%,40.56359999999999
2024,-2.5%,38.631999999999984
2024,-3%,36.70039999999998
2024,-3.5%,34.76879999999998
2024,-4% pro Jahr,32.837199999999974
2025,-0.5%,46.116949999999996
2025,-1%,43.94389999999999
2025,-1.5%,41.77084999999999
2025,-2%,39.597799999999985
2025,-2.5%,37.42474999999998
2025,-3%,35.25169999999998
2025,-3.5%,33.078649999999975
2025,-4% pro Jahr,30.905599999999975
2026,-0.5%,45.875499999999995
2026,-1%,43.46099999999999
2026,-1.5%,41.04649999999999
2026,-2%,38.631999999999984
2026,-2.5%,36.21749999999998
2026,-3%,33.802999999999976
2026,-3.5%,31.388499999999976
2026,-4% pro Jahr,28.973999999999975
2027,-0.5%,45.634049999999995
2027,-1%,42.97809999999999
2027,-1.5%,40.322149999999986
2027,-2%,37.66619999999998
2027,-2.5%,35.01024999999998
2027,-3%,32.354299999999974
2027,-3.5%,29.698349999999976
2027,-4% pro Jahr,27.042399999999976
2028,-0.5%,45.392599999999995
2028,-1%,42.49519999999999
2028,-1.5%,39.597799999999985
2028,-2%,36.70039999999998
2028,-2.5%,33.802999999999976
2028,-3%,30.905599999999975
2028,-3.5%,28.008199999999977
2028,-4% pro Jahr,25.110799999999976
2029,-0.5%,45.151149999999994
2029,-1%,42.01229999999999
2029,-1.5%,38.873449999999984
2029,-2%,35.73459999999998
2029,-2.5%,32.595749999999974
2029,-3%,29.456899999999976
2029,-3.5%,26.318049999999978
2029,-4% pro Jahr,23.179199999999977
2030,-0.5%,44.909699999999994
2030,-1%,41.52939999999999
2030,-1.5%,38.14909999999998
2030,-2%,34.76879999999998
2030,-2.5%,31.388499999999976
2030,-3%,28.008199999999977
2030,-3.5%,24.62789999999998
2030,-4% pro Jahr,21.247599999999977
2031,-0.5%,44.66824999999999
2031,-1%,41.04649999999999
2031,-1.5%,37.42474999999998
2031,-2%,33.802999999999976
2031,-2.5%,30.181249999999977
2031,-3%,26.55949999999998
2031,-3.5%,22.93774999999998
2031,-4% pro Jahr,19.315999999999978
2032,-0.5%,44.42679999999999
2032,-1%,40.56359999999999
2032,-1.5%,36.70039999999998
2032,-2%,32.837199999999974
2032,-2.5%,28.97399999999998
2032,-3%,25.11079999999998
2032,-3.5%,21.24759999999998
2032,-4% pro Jahr,17.384399999999978
2033,-0.5%,44.18534999999999
2033,-1%,40.080699999999986
2033,-1.5%,35.97604999999998
2033,-2%,31.871399999999973
2033,-2.5%,27.76674999999998
2033,-3%,23.66209999999998
2033,-3.5%,19.55744999999998
2033,-4% pro Jahr,15.452799999999979
2034,-0.5%,43.94389999999999
2034,-1%,39.597799999999985
2034,-1.5%,35.25169999999998
2034,-2%,30.90559999999997
2034,-2.5%,26.559499999999982
2034,-3%,22.213399999999982
2034,-3.5%,17.867299999999982
2034,-4% pro Jahr,13.521199999999979
2035,-0.5%,43.70244999999999
2035,-1%,39.114899999999984
2035,-1.5%,34.52734999999998
2035,-2%,29.93979999999997
2035,-2.5%,25.352249999999984
2035,-3%,20.764699999999984
2035,-3.5%,16.177149999999983
2035,-4% pro Jahr,11.58959999999998
2036,-0.5%,43.46099999999999
2036,-1%,38.631999999999984
2036,-1.5%,33.802999999999976
2036,-2%,28.97399999999997
2036,-2.5%,24.144999999999985
2036,-3%,19.315999999999985
2036,-3.5%,14.486999999999984
2036,-4% pro Jahr,9.65799999999998
2037,-0.5%,43.21954999999999
2037,-1%,38.14909999999998
2037,-1.5%,33.078649999999975
2037,-2%,28.008199999999967
2037,-2.5%,22.937749999999987
2037,-3%,17.867299999999986
2037,-3.5%,12.796849999999985
2037,-4% pro Jahr,7.72639999999998
2038,-0.5%,42.97809999999999
2038,-1%,37.66619999999998
2038,-1.5%,32.354299999999974
2038,-2%,27.042399999999965
2038,-2.5%,21.73049999999999
2038,-3%,16.418599999999987
2038,-3.5%,11.106699999999986
2038,-4% pro Jahr,5.794799999999981
2039,-0.5%,42.73664999999999
2039,-1%,37.18329999999998
2039,-1.5%,31.629949999999972
2039,-2%,26.076599999999964
2039,-2.5%,20.52324999999999
2039,-3%,14.969899999999987
2039,-3.5%,9.416549999999987
2039,-4% pro Jahr,3.863199999999981
2040,-0.5%,42.49519999999999
2040,-1%,36.70039999999998
2040,-1.5%,30.90559999999997
2040,-2%,25.110799999999962
2040,-2.5%,19.315999999999992
2040,-3%,13.521199999999986
2040,-3.5%,7.726399999999987
2040,-4% pro Jahr,1.9315999999999809
2041,-0.5%,42.25374999999999
2041,-1%,36.21749999999998
2041,-1.5%,30.18124999999997
2041,-2%,24.14499999999996
2041,-2.5%,18.108749999999993
2041,-3%,12.072499999999986
2041,-3.5%,6.036249999999987
2041,-4% pro Jahr,-1.9095836023552692e-14
2042,-0.5%,42.01229999999999
2042,-1%,35.73459999999998
2042,-1.5%,29.45689999999997
2042,-2%,23.17919999999996
2042,-2.5%,16.901499999999995
2042,-3%,10.623799999999985
2042,-3.5%,4.3460999999999865
2043,-0.5%,41.77084999999999
2043,-1%,35.25169999999998
2043,-1.5%,28.732549999999968
2043,-2%,22.213399999999957
2043,-2.5%,15.694249999999995
2043,-3%,9.175099999999984
2043,-3.5%,2.6559499999999865
2044,-0.5%,41.52939999999999
2044,-1%,34.76879999999998
2044,-1.5%,28.008199999999967
2044,-2%,21.247599999999956
2044,-2.5%,14.486999999999995
2044,-3%,7.726399999999984
2044,-3.5%,0.9657999999999867
2045,-0.5%,41.28794999999999
2045,-1%,34.28589999999998
2045,-1.5%,27.283849999999966
2045,-2%,20.281799999999954
2045,-2.5%,13.279749999999995
2045,-3%,6.277699999999983
2045,-3.5%,-0.7243500000000132
2046,-0.5%,41.04649999999999
2046,-1%,33.802999999999976
2046,-1.5%,26.559499999999964
2046,-2%,19.315999999999953
2046,-2.5%,12.072499999999994
2046,-3%,4.828999999999983
2047,-0.5%,40.80504999999999
2047,-1%,33.320099999999975
2047,-1.5%,25.835149999999963
2047,-2%,18.35019999999995
2047,-2.5%,10.865249999999994
2047,-3%,3.3802999999999828
2048,-0.5%,40.56359999999999
2048,-1%,32.837199999999974
2048,-1.5%,25.110799999999962
2048,-2%,17.38439999999995
2048,-2.5%,9.657999999999994
2048,-3%,1.9315999999999827
2049,-0.5%,40.322149999999986
2049,-1%,32.354299999999974
2049,-1.5%,24.38644999999996
2049,-2%,16.418599999999948
2049,-2.5%,8.450749999999994
2049,-3%,0.48289999999998257
2050,-0.5%,40.080699999999986
2050,-1%,31.871399999999973
2050,-1.5%,23.66209999999996
2050,-2%,15.452799999999948
2050,-2.5%,7.243499999999994
2050,-3%,-0.9658000000000175
2051,-0.5%,39.839249999999986
2051,-1%,31.388499999999972
2051,-1.5%,22.93774999999996
2051,-2%,14.486999999999949
2051,-2.5%,6.036249999999994
2052,-0.5%,39.597799999999985
2052,-1%,30.90559999999997
2052,-1.5%,22.213399999999957
2052,-2%,13.521199999999949
2052,-2.5%,4.8289999999999935
2053,-0.5%,39.356349999999985
2053,-1%,30.42269999999997
2053,-1.5%,21.489049999999956
2053,-2%,12.555399999999949
2053,-2.5%,3.6217499999999934
2054,-0.5%,39.114899999999984
2054,-1%,29.93979999999997
2054,-1.5%,20.764699999999955
2054,-2%,11.58959999999995
2054,-2.5%,2.414499999999993
2055,-0.5%,38.873449999999984
2055,-1%,29.45689999999997
2055,-1.5%,20.040349999999954
2055,-2%,10.62379999999995
2055,-2.5%,1.2072499999999933
2056,-0.5%,38.631999999999984
2056,-1%,28.97399999999997
2056,-1.5%,19.315999999999953
2056,-2%,9.65799999999995
2056,-2.5%,-6.661338147750939e-15
2057,-0.5%,38.39054999999998
2057,-1%,28.491099999999967
2057,-1.5%,18.59164999999995
2057,-2%,8.69219999999995
2058,-0.5%,38.14909999999998
2058,-1%,28.008199999999967
2058,-1.5%,17.86729999999995
2058,-2%,7.72639999999995
2059,-0.5%,37.90764999999998
2059,-1%,27.525299999999966
2059,-1.5%,17.14294999999995
2059,-2%,6.76059999999995
2060,-0.5%,37.66619999999998
2060,-1%,27.042399999999965
2060,-1.5%,16.418599999999948
2060,-2%,5.794799999999951
2061,-0.5%,37.42474999999998
2061,-1%,26.559499999999964
2061,-1.5%,15.694249999999949
2061,-2%,4.828999999999951
2062,-0.5%,37.18329999999998
2062,-1%,26.076599999999964
2062,-1.5%,14.96989999999995
2062,-2%,3.863199999999951
2063,-0.5%,36.94184999999998
2063,-1%,25.593699999999963
2063,-1.5%,14.24554999999995
2063,-2%,2.8973999999999513
2064,-0.5%,36.70039999999998
2064,-1%,25.110799999999962
2064,-1.5%,13.52119999999995
2064,-2%,1.9315999999999514
2065,-0.5%,36.45894999999998
2065,-1%,24.62789999999996
2065,-1.5%,12.796849999999951
2065,-2%,0.9657999999999514
2066,-0.5%,36.21749999999998
2066,-1%,24.14499999999996
2066,-1.5%,12.072499999999952
2066,-2%,-4.8627768478581856e-14
2067,-0.5%,35.97604999999998
2067,-1%,23.66209999999996
2067,-1.5%,11.348149999999952
2068,-0.5%,35.73459999999998
2068,-1%,23.17919999999996
2068,-1.5%,10.623799999999953
2069,-0.5%,35.49314999999998
2069,-1%,22.696299999999958
2069,-1.5%,9.899449999999954
2070,-0.5%,35.25169999999998
2070,-1%,22.213399999999957
2070,-1.5%,9.175099999999954
2071,-0.5%,35.01024999999998
2071,-1%,21.730499999999957
2071,-1.5%,8.450749999999955
2072,-0.5%,34.76879999999998
2072,-1%,21.247599999999956
2072,-1.5%,7.726399999999955
2073,-0.5%,34.52734999999998
2073,-1%,20.764699999999955
2073,-1.5%,7.002049999999954
2074,-0.5%,34.28589999999998
2074,-1%,20.281799999999954
2074,-1.5%,6.277699999999954
2075,-0.5%,34.044449999999976
2075,-1%,19.798899999999954
2075,-1.5%,5.553349999999954
2076,-0.5%,33.802999999999976
2076,-1%,19.315999999999953
2076,-1.5%,4.8289999999999536
2077,-0.5%,33.561549999999976
2077,-1%,18.833099999999952
2077,-1.5%,4.104649999999953
2078,-0.5%,33.320099999999975
2078,-1%,18.35019999999995
2078,-1.5%,3.380299999999953
2079,-0.5%,33.078649999999975
2079,-1%,17.86729999999995
2079,-1.5%,2.6559499999999527
2080,-0.5%,32.837199999999974
2080,-1%,17.38439999999995
2080,-1.5%,1.9315999999999527
```

Quelle: [Bafu](https://www.bafu.admin.ch/bafu/de/home/themen/klima/inkuerze.html). Berücksichtigt sind die Emissionen im Inland, ohne den Flugverkehr und die grauen Emissionen aus importierten Produkten.

<hr /></section>

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesqueeu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo,fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut,imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputateeleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac,enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellusviverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiamultricies nisi vel augue.

<section><h6>ARTICLECOLLECTION</h6>

```
{
  "membersOnly": true,
  "unauthorizedText": ""
}
```

## Die lange Sicht auf die Klimapolitik der Schweiz

<section><h6>TEASERGROUP</h6>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-co2-pro-kopf?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-auf-langer-sicht?autoSlug",
  "titleSize": "standard",
  "id": "mpFAm8IV7",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Auf lange Sicht

# Das kleine Einmaleins der Klimapolitik

## 

#### Wie schnell muss die Schweiz ihre Treibhausgasemissionen reduzieren? Zwei Grafiken geben darauf eine intuitive Antwort.

Von [Simon Schmid](/~eca9ee2c-4678-4f63-8564-651293df2b97), 26.11.2018

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#D44338",
  "onlyImage": false,
  "url": "https://github.com/republik/article-klima-ameise?autoSlug",
  "kind": "scribble",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-aus-der-arena?autoSlug",
  "titleSize": "standard",
  "id": "CwhgqgGfmE",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Aus der Arena

# Unser doppeltes Klimadilemma

## 

#### Weshalb es auch für die kleine Schweiz von grossem Interesse sein sollte, den Klimawandel zu bremsen.

Von [Simon Schmid](/~eca9ee2c-4678-4f63-8564-651293df2b97), 14.11.2018

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-eine-kleine-energiegeschichte?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-auf-langer-sicht?autoSlug",
  "titleSize": "standard",
  "id": "gbQaIEfvxg",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Auf lange Sicht

# Eine kleine Energie-geschichte

## 

#### Wie die Schweiz in nur 100 Jahren zum Vielverbraucher fossiler Treibstoffe wurde – und wie sich der Energiehaushalt des Landes in den nächsten Jahrzehnten verändern muss.

Von [Simon Schmid](/~eca9ee2c-4678-4f63-8564-651293df2b97), 01.07.2019

<hr /></section>

<hr /></section>

<hr /></section>

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesqueeu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo,fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut,imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputateeleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac,enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellusviverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiamultricies nisi vel augue.

<section><h6>CHART</h6>

```
{
  "type": "TimeBar",
  "x": "date",
  "color": "category",
  "colorSort": "none",
  "padding": 0,
  "unit": "Petajoule",
  "xTicks": [
    1918,
    1945,
    1973,
    2000,
    2017
  ],
  "yTicks": [
    0,
    200,
    400,
    600,
    800
  ],
  "domain": [
    0,
    900
  ],
  "colorRange": [
    "#408000",
    "#734d26",
    "#777777",
    "#e62e00",
    "#ff9900",
    "#ffff00",
    "#1a8cff",
    "#00cc00"
  ],
  "height": 350
}
```

### Aufgefächert

Energieendverbrauch in der Schweiz

```
date,category,value
1910,Holz,17.19
1910,Kohle,76.31
1910,Industrieabfälle,0
1910,Erdölbrennstoffe,0.24
1910,Erdöltreibstoffe,0.5
1910,Gas,2.22
1910,Elektrizität,3.53
1910,Übrige erneuerbare Energien,0
1911,Holz,17.19
1911,Kohle,84.66
1911,Industrieabfälle,0
1911,Erdölbrennstoffe,0.34
1911,Erdöltreibstoffe,0.62
1911,Gas,2.35
1911,Elektrizität,4.33
1911,Übrige erneuerbare Energien,0
1912,Holz,17.19
1912,Kohle,85.38
1912,Industrieabfälle,0
1912,Erdölbrennstoffe,0.35
1912,Erdöltreibstoffe,0.66
1912,Gas,2.57
1912,Elektrizität,5.04
1912,Übrige erneuerbare Energien,0
1913,Holz,17.19
1913,Kohle,89.45
1913,Industrieabfälle,0
1913,Erdölbrennstoffe,0.34
1913,Erdöltreibstoffe,0.69
1913,Gas,2.55
1913,Elektrizität,5.45
1913,Übrige erneuerbare Energien,0
1914,Holz,16.83
1914,Kohle,86.9
1914,Industrieabfälle,0
1914,Erdölbrennstoffe,0.15
1914,Erdöltreibstoffe,0.52
1914,Gas,2.57
1914,Elektrizität,5.67
1914,Übrige erneuerbare Energien,0
1915,Holz,14.93
1915,Kohle,87.74
1915,Industrieabfälle,0
1915,Erdölbrennstoffe,0.041
1915,Erdöltreibstoffe,0.45
1915,Gas,2.66
1915,Elektrizität,6.24
1915,Übrige erneuerbare Energien,0
1916,Holz,12.59
1916,Kohle,82.78
1916,Industrieabfälle,0
1916,Erdölbrennstoffe,0.012
1916,Erdöltreibstoffe,0.17
1916,Gas,2.9
1916,Elektrizität,6.84
1916,Übrige erneuerbare Energien,0
1917,Holz,13.58
1917,Kohle,68.38
1917,Industrieabfälle,0
1917,Erdölbrennstoffe,0.003
1917,Erdöltreibstoffe,0.31
1917,Gas,2.19
1917,Elektrizität,7.56
1917,Übrige erneuerbare Energien,0
1918,Holz,18.33
1918,Kohle,63.88
1918,Industrieabfälle,0
1918,Erdölbrennstoffe,0.01
1918,Erdöltreibstoffe,0.29
1918,Gas,1.92
1918,Elektrizität,8.39
1918,Übrige erneuerbare Energien,0
1919,Holz,19.75
1919,Kohle,48.61
1919,Industrieabfälle,0
1919,Erdölbrennstoffe,0.049
1919,Erdöltreibstoffe,0.59
1919,Gas,1.85
1919,Elektrizität,8.14
1919,Übrige erneuerbare Energien,0
1920,Holz,17.49
1920,Kohle,64.14
1920,Industrieabfälle,0
1920,Erdölbrennstoffe,0.37
1920,Erdöltreibstoffe,1.49
1920,Gas,2
1920,Elektrizität,7.63
1920,Übrige erneuerbare Energien,0
1921,Holz,16.76
1921,Kohle,48.51
1921,Industrieabfälle,0
1921,Erdölbrennstoffe,0.39
1921,Erdöltreibstoffe,0.96
1921,Gas,2
1921,Elektrizität,7.2
1921,Übrige erneuerbare Energien,0
1922,Holz,18.99
1922,Kohle,60.48
1922,Industrieabfälle,0
1922,Erdölbrennstoffe,1.01
1922,Erdöltreibstoffe,1.64
1922,Gas,2.11
1922,Elektrizität,7.85
1922,Übrige erneuerbare Energien,0
1923,Holz,21.88
1923,Kohle,75.48
1923,Industrieabfälle,0
1923,Erdölbrennstoffe,1.2
1923,Erdöltreibstoffe,1.87
1923,Gas,2.26
1923,Elektrizität,8.57
1923,Übrige erneuerbare Energien,0
1924,Holz,21.07
1924,Kohle,70.06
1924,Industrieabfälle,0
1924,Erdölbrennstoffe,1.52
1924,Erdöltreibstoffe,2
1924,Gas,2.4
1924,Elektrizität,9.76
1924,Übrige erneuerbare Energien,0
1925,Holz,19.93
1925,Kohle,72.65
1925,Industrieabfälle,0
1925,Erdölbrennstoffe,1.56
1925,Erdöltreibstoffe,2.92
1925,Gas,2.57
1925,Elektrizität,10.33
1925,Übrige erneuerbare Energien,0
1926,Holz,20.01
1926,Kohle,71.98
1926,Industrieabfälle,0
1926,Erdölbrennstoffe,1.76
1926,Erdöltreibstoffe,3.19
1926,Gas,2.72
1926,Elektrizität,10.87
1926,Übrige erneuerbare Energien,0
1927,Holz,19.11
1927,Kohle,81.56
1927,Industrieabfälle,0
1927,Erdölbrennstoffe,2.01
1927,Erdöltreibstoffe,3.98
1927,Gas,2.9
1927,Elektrizität,11.56
1927,Übrige erneuerbare Energien,0
1928,Holz,19.42
1928,Kohle,80.71
1928,Industrieabfälle,0
1928,Erdölbrennstoffe,2.37
1928,Erdöltreibstoffe,4.95
1928,Gas,3.1
1928,Elektrizität,12.24
1928,Übrige erneuerbare Energien,0
1929,Holz,20.06
1929,Kohle,94.01
1929,Industrieabfälle,0
1929,Erdölbrennstoffe,2.98
1929,Erdöltreibstoffe,5.86
1929,Gas,3.33
1929,Elektrizität,13.05
1929,Übrige erneuerbare Energien,0
1930,Holz,19.31
1930,Kohle,84.87
1930,Industrieabfälle,0
1930,Erdölbrennstoffe,3.31
1930,Erdöltreibstoffe,6.69
1930,Gas,3.47
1930,Elektrizität,12.83
1930,Übrige erneuerbare Energien,0
1931,Holz,20.39
1931,Kohle,87.29
1931,Industrieabfälle,0
1931,Erdölbrennstoffe,3.88
1931,Erdöltreibstoffe,7.73
1931,Gas,3.64
1931,Elektrizität,12.07
1931,Übrige erneuerbare Energien,0
1932,Holz,19.26
1932,Kohle,86.08
1932,Industrieabfälle,0
1932,Erdölbrennstoffe,5.17
1932,Erdöltreibstoffe,8.77
1932,Gas,3.8
1932,Elektrizität,11.55
1932,Übrige erneuerbare Energien,0
1933,Holz,19
1933,Kohle,81.39
1933,Industrieabfälle,0
1933,Erdölbrennstoffe,6.07
1933,Erdöltreibstoffe,8.47
1933,Gas,3.82
1933,Elektrizität,12.27
1933,Übrige erneuerbare Energien,0
1934,Holz,19.06
1934,Kohle,80.97
1934,Industrieabfälle,0
1934,Erdölbrennstoffe,6.43
1934,Erdöltreibstoffe,9.51
1934,Gas,3.88
1934,Elektrizität,12.8
1934,Übrige erneuerbare Energien,0
1935,Holz,19.83
1935,Kohle,79.8
1935,Industrieabfälle,0
1935,Erdölbrennstoffe,6.76
1935,Erdöltreibstoffe,9.29
1935,Gas,3.87
1935,Elektrizität,13.53
1935,Übrige erneuerbare Energien,0
1936,Holz,18.1
1936,Kohle,82.03
1936,Industrieabfälle,0
1936,Erdölbrennstoffe,6.97
1936,Erdöltreibstoffe,8.52
1936,Gas,3.85
1936,Elektrizität,14.46
1936,Übrige erneuerbare Energien,0
1937,Holz,18.02
1937,Kohle,85.22
1937,Industrieabfälle,0
1937,Erdölbrennstoffe,6.45
1937,Erdöltreibstoffe,8.66
1937,Gas,3.92
1937,Elektrizität,16.96
1937,Übrige erneuerbare Energien,0
1938,Holz,17.95
1938,Kohle,85.19
1938,Industrieabfälle,0
1938,Erdölbrennstoffe,6.77
1938,Erdöltreibstoffe,9.15
1938,Gas,4.02
1938,Elektrizität,16.9
1938,Übrige erneuerbare Energien,0
1939,Holz,18.16
1939,Kohle,86.45
1939,Industrieabfälle,0
1939,Erdölbrennstoffe,7.7
1939,Erdöltreibstoffe,8.64
1939,Gas,4.02
1939,Elektrizität,18.39
1939,Übrige erneuerbare Energien,0
1940,Holz,23.12
1940,Kohle,70.5
1940,Industrieabfälle,0
1940,Erdölbrennstoffe,4.8
1940,Erdöltreibstoffe,5.76
1940,Gas,4.24
1940,Elektrizität,19.63
1940,Übrige erneuerbare Energien,0
1941,Holz,31.27
1941,Kohle,62.46
1941,Industrieabfälle,0
1941,Erdölbrennstoffe,1.94
1941,Erdöltreibstoffe,2.14
1941,Gas,3.49
1941,Elektrizität,20.57
1941,Übrige erneuerbare Energien,0
1942,Holz,30.83
1942,Kohle,58.46
1942,Industrieabfälle,0
1942,Erdölbrennstoffe,1.51
1942,Erdöltreibstoffe,1.48
1942,Gas,3.39
1942,Elektrizität,20.49
1942,Übrige erneuerbare Energien,0
1943,Holz,31.27
1943,Kohle,51.74
1943,Industrieabfälle,0
1943,Erdölbrennstoffe,1.32
1943,Erdöltreibstoffe,1.28
1943,Gas,3.35
1943,Elektrizität,22.45
1943,Übrige erneuerbare Energien,0
1944,Holz,30.26
1944,Kohle,41.32
1944,Industrieabfälle,0
1944,Erdölbrennstoffe,0.65
1944,Erdöltreibstoffe,1.51
1944,Gas,3.48
1944,Elektrizität,24.2
1944,Übrige erneuerbare Energien,0
1945,Holz,32.92
1945,Kohle,42.62
1945,Industrieabfälle,0
1945,Erdölbrennstoffe,0.67
1945,Erdöltreibstoffe,0.48
1945,Gas,2.43
1945,Elektrizität,27.55
1945,Übrige erneuerbare Energien,0
1946,Holz,34.23
1946,Kohle,44.94
1946,Industrieabfälle,0
1946,Erdölbrennstoffe,8.69
1946,Erdöltreibstoffe,6.3
1946,Gas,2.82
1946,Elektrizität,29.65
1946,Übrige erneuerbare Energien,0
1947,Holz,22.31
1947,Kohle,56.48
1947,Industrieabfälle,0
1947,Erdölbrennstoffe,17.45
1947,Erdöltreibstoffe,10.91
1947,Gas,3.3
1947,Elektrizität,28.22
1947,Übrige erneuerbare Energien,0
1948,Holz,23.03
1948,Kohle,59.67
1948,Industrieabfälle,0
1948,Erdölbrennstoffe,16.06
1948,Erdöltreibstoffe,13.63
1948,Gas,3.65
1948,Elektrizität,31.95
1948,Übrige erneuerbare Energien,0
1949,Holz,20.73
1949,Kohle,59.78
1949,Industrieabfälle,0
1949,Erdölbrennstoffe,19.36
1949,Erdöltreibstoffe,13.87
1949,Gas,3.74
1949,Elektrizität,28.33
1949,Übrige erneuerbare Energien,0
1950,Holz,21.72
1950,Kohle,67.69
1950,Industrieabfälle,0
1950,Erdölbrennstoffe,23.67
1950,Erdöltreibstoffe,19.07
1950,Gas,3.77
1950,Elektrizität,31.78
1950,Übrige erneuerbare Energien,0
1951,Holz,21.55
1951,Kohle,70.75
1951,Industrieabfälle,0
1951,Erdölbrennstoffe,26.47
1951,Erdöltreibstoffe,19.86
1951,Gas,3.87
1951,Elektrizität,36.78
1951,Übrige erneuerbare Energien,0
1952,Holz,21.32
1952,Kohle,74.12
1952,Industrieabfälle,0
1952,Erdölbrennstoffe,27.58
1952,Erdöltreibstoffe,22.82
1952,Gas,3.93
1952,Elektrizität,37.77
1952,Übrige erneuerbare Energien,0
1953,Holz,19.94
1953,Kohle,61.56
1953,Industrieabfälle,0
1953,Erdölbrennstoffe,30.41
1953,Erdöltreibstoffe,24.48
1953,Gas,3.97
1953,Elektrizität,39.2
1953,Übrige erneuerbare Energien,0
1954,Holz,18.28
1954,Kohle,71.99
1954,Industrieabfälle,0
1954,Erdölbrennstoffe,40.68
1954,Erdöltreibstoffe,26.59
1954,Gas,4.05
1954,Elektrizität,40.56
1954,Übrige erneuerbare Energien,0
1955,Holz,18.12
1955,Kohle,75.33
1955,Industrieabfälle,0
1955,Erdölbrennstoffe,47.69
1955,Erdöltreibstoffe,30.75
1955,Gas,4.03
1955,Elektrizität,44.78
1955,Übrige erneuerbare Energien,0
1956,Holz,17.25
1956,Kohle,81.28
1956,Industrieabfälle,0
1956,Erdölbrennstoffe,64
1956,Erdöltreibstoffe,37.07
1956,Gas,4.19
1956,Elektrizität,46.12
1956,Übrige erneuerbare Energien,0
1957,Holz,17.82
1957,Kohle,74.92
1957,Industrieabfälle,0
1957,Erdölbrennstoffe,62.49
1957,Erdöltreibstoffe,37.8
1957,Gas,4.13
1957,Elektrizität,48.12
1957,Übrige erneuerbare Energien,0
1958,Holz,16.56
1958,Kohle,67.36
1958,Industrieabfälle,0
1958,Erdölbrennstoffe,74.75
1958,Erdöltreibstoffe,43.18
1958,Gas,4.1
1958,Elektrizität,50.12
1958,Übrige erneuerbare Energien,0
1959,Holz,15.11
1959,Kohle,68.51
1959,Industrieabfälle,0
1959,Erdölbrennstoffe,77.19
1959,Erdöltreibstoffe,48.79
1959,Gas,4.06
1959,Elektrizität,51.78
1959,Übrige erneuerbare Energien,0
1960,Holz,14.52
1960,Kohle,68.08
1960,Industrieabfälle,0
1960,Erdölbrennstoffe,95.3
1960,Erdöltreibstoffe,55.31
1960,Gas,4.12
1960,Elektrizität,57.21
1960,Übrige erneuerbare Energien,0
1961,Holz,14.17
1961,Kohle,63.27
1961,Industrieabfälle,0
1961,Erdölbrennstoffe,103.56
1961,Erdöltreibstoffe,66.09
1961,Gas,4.09
1961,Elektrizität,60.27
1961,Übrige erneuerbare Energien,0
1962,Holz,16.15
1962,Kohle,68.49
1962,Industrieabfälle,0
1962,Erdölbrennstoffe,134.47
1962,Erdöltreibstoffe,71.26
1962,Gas,4.21
1962,Elektrizität,63.78
1962,Übrige erneuerbare Energien,0
1963,Holz,16.18
1963,Kohle,68.15
1963,Industrieabfälle,0
1963,Erdölbrennstoffe,169.34
1963,Erdöltreibstoffe,82.79
1963,Gas,4.4
1963,Elektrizität,66.54
1963,Übrige erneuerbare Energien,0
1964,Holz,16.22
1964,Kohle,54.51
1964,Industrieabfälle,0
1964,Erdölbrennstoffe,182.22
1964,Erdöltreibstoffe,91.49
1964,Gas,4.28
1964,Elektrizität,69.65
1964,Übrige erneuerbare Energien,0
1965,Holz,16.83
1965,Kohle,43.98
1965,Industrieabfälle,0
1965,Erdölbrennstoffe,212.98
1965,Erdöltreibstoffe,96.71
1965,Gas,4.36
1965,Elektrizität,72.8
1965,Übrige erneuerbare Energien,0
1966,Holz,14.73
1966,Kohle,36.07
1966,Industrieabfälle,0
1966,Erdölbrennstoffe,216.96
1966,Erdöltreibstoffe,104.02
1966,Gas,4.35
1966,Elektrizität,74.55
1966,Übrige erneuerbare Energien,0
1967,Holz,14.29
1967,Kohle,30.7
1967,Industrieabfälle,0
1967,Erdölbrennstoffe,235.22
1967,Erdöltreibstoffe,108.47
1967,Gas,4.47
1967,Elektrizität,77.5
1967,Übrige erneuerbare Energien,0
1968,Holz,13.63
1968,Kohle,29.93
1968,Industrieabfälle,0
1968,Erdölbrennstoffe,261.55
1968,Erdöltreibstoffe,115.58
1968,Gas,4.7
1968,Elektrizität,80.77
1968,Übrige erneuerbare Energien,0
1969,Holz,12.31
1969,Kohle,27.23
1969,Industrieabfälle,0
1969,Erdölbrennstoffe,291.15
1969,Erdöltreibstoffe,125.13
1969,Gas,5.95
1969,Elektrizität,85.32
1969,Übrige erneuerbare Energien,0
1970,Holz,10.11
1970,Kohle,24.44
1970,Industrieabfälle,0
1970,Erdölbrennstoffe,316.51
1970,Erdöltreibstoffe,138.06
1970,Gas,6.62
1970,Elektrizität,90.31
1970,Übrige erneuerbare Energien,0
1971,Holz,9.67
1971,Kohle,16.5
1971,Industrieabfälle,0
1971,Erdölbrennstoffe,334.49
1971,Erdöltreibstoffe,150.26
1971,Gas,7.6
1971,Elektrizität,94.49
1971,Übrige erneuerbare Energien,0
1972,Holz,9.23
1972,Kohle,13.79
1972,Industrieabfälle,0
1972,Erdölbrennstoffe,336.47
1972,Erdöltreibstoffe,160.72
1972,Gas,8.2
1972,Elektrizität,97.71
1972,Übrige erneuerbare Energien,0
1973,Holz,10.11
1973,Kohle,12.96
1973,Industrieabfälle,0
1973,Erdölbrennstoffe,371.15
1973,Erdöltreibstoffe,165.33
1973,Gas,9.55
1973,Elektrizität,103.59
1973,Übrige erneuerbare Energien,0
1974,Holz,8.35
1974,Kohle,12.13
1974,Industrieabfälle,0
1974,Erdölbrennstoffe,325.81
1974,Erdöltreibstoffe,155.76
1974,Gas,13.55
1974,Elektrizität,106.44
1974,Übrige erneuerbare Energien,0
1975,Holz,8.35
1975,Kohle,9.58
1975,Industrieabfälle,0
1975,Erdölbrennstoffe,314.83
1975,Erdöltreibstoffe,156.07
1975,Gas,18.87
1975,Elektrizität,104.05
1975,Übrige erneuerbare Energien,0
1976,Holz,8.35
1976,Kohle,8.6
1976,Industrieabfälle,0
1976,Erdölbrennstoffe,320.7
1976,Erdöltreibstoffe,157
1976,Gas,20.43
1976,Elektrizität,107.65
1976,Übrige erneuerbare Energien,0
1977,Holz,8.35
1977,Kohle,10.5
1977,Industrieabfälle,0
1977,Erdölbrennstoffe,313.4
1977,Erdöltreibstoffe,167.2
1977,Gas,24.12
1977,Elektrizität,112.64
1977,Übrige erneuerbare Energien,0
1978,Holz,7.91
1978,Kohle,9.2
1978,Industrieabfälle,3.6
1978,Erdölbrennstoffe,335.6
1978,Erdöltreibstoffe,170
1978,Gas,22.45
1978,Elektrizität,116.87
1978,Übrige erneuerbare Energien,5.76
1979,Holz,9.01
1979,Kohle,9.44
1979,Industrieabfälle,3.7
1979,Erdölbrennstoffe,313.93
1979,Erdöltreibstoffe,168.77
1979,Gas,25.42
1979,Elektrizität,121.56
1979,Übrige erneuerbare Energien,6.07
1980,Holz,26.28
1980,Kohle,13.63
1980,Industrieabfälle,3.7
1980,Erdölbrennstoffe,310.66
1980,Erdöltreibstoffe,178.82
1980,Gas,30.37
1980,Elektrizität,126.91
1980,Übrige erneuerbare Energien,7.92
1981,Holz,25.48
1981,Kohle,20.11
1981,Industrieabfälle,4.6
1981,Erdölbrennstoffe,284.09
1981,Erdöltreibstoffe,181.62
1981,Gas,33.37
1981,Elektrizität,130.3
1981,Übrige erneuerbare Energien,8.32
1982,Holz,24.93
1982,Kohle,17.79
1982,Industrieabfälle,4.88
1982,Erdölbrennstoffe,264.94
1982,Erdöltreibstoffe,183.72
1982,Gas,35.83
1982,Elektrizität,132.23
1982,Übrige erneuerbare Energien,8.43
1983,Holz,25.34
1983,Kohle,15.34
1983,Industrieabfälle,5.16
1983,Erdölbrennstoffe,268.48
1983,Erdöltreibstoffe,191.71
1983,Gas,39.92
1983,Elektrizität,136.69
1983,Übrige erneuerbare Energien,8.61
1984,Holz,26.56
1984,Kohle,19.77
1984,Industrieabfälle,6.28
1984,Erdölbrennstoffe,272.33
1984,Erdöltreibstoffe,198.91
1984,Gas,45.41
1984,Elektrizität,142.79
1984,Übrige erneuerbare Energien,9.21
1985,Holz,27.03
1985,Kohle,19.79
1985,Industrieabfälle,6.4
1985,Erdölbrennstoffe,270.78
1985,Erdöltreibstoffe,201.05
1985,Gas,47.66
1985,Elektrizität,148.76
1985,Übrige erneuerbare Energien,9.43
1986,Holz,26.29
1986,Kohle,17.2
1986,Industrieabfälle,6.53
1986,Erdölbrennstoffe,274.26
1986,Erdöltreibstoffe,210.3
1986,Gas,48.98
1986,Elektrizität,152.45
1986,Übrige erneuerbare Energien,9.86
1987,Holz,26.38
1987,Kohle,16.42
1987,Industrieabfälle,6.56
1987,Erdölbrennstoffe,268.44
1987,Erdöltreibstoffe,216.88
1987,Gas,52.82
1987,Elektrizität,156.93
1987,Übrige erneuerbare Energien,11.25
1988,Holz,25.01
1988,Kohle,14.03
1988,Industrieabfälle,6.59
1988,Erdölbrennstoffe,261.76
1988,Erdöltreibstoffe,227.3
1988,Gas,53.8
1988,Elektrizität,159.58
1988,Übrige erneuerbare Energien,10.72
1989,Holz,24.87
1989,Kohle,14.01
1989,Industrieabfälle,6.64
1989,Erdölbrennstoffe,247.02
1989,Erdöltreibstoffe,236.01
1989,Gas,58.83
1989,Elektrizität,163.81
1989,Übrige erneuerbare Energien,10.78
1990,Holz,28.51
1990,Kohle,14.36
1990,Industrieabfälle,8.68
1990,Erdölbrennstoffe,243.6
1990,Erdöltreibstoffe,253.22
1990,Gas,63.64
1990,Elektrizität,167.68
1990,Übrige erneuerbare Energien,14.51
1991,Holz,31.42
1991,Kohle,12.54
1991,Industrieabfälle,10.74
1991,Erdölbrennstoffe,261.65
1991,Erdöltreibstoffe,258.94
1991,Gas,71.45
1991,Elektrizität,171.31
1991,Übrige erneuerbare Energien,16.68
1992,Holz,30.4
1992,Kohle,8.66
1992,Industrieabfälle,10.72
1992,Erdölbrennstoffe,257.87
1992,Erdöltreibstoffe,265.89
1992,Gas,75.36
1992,Elektrizität,172.32
1992,Übrige erneuerbare Energien,16.59
1993,Holz,30.48
1993,Kohle,7.28
1993,Industrieabfälle,11.96
1993,Erdölbrennstoffe,245.52
1993,Erdöltreibstoffe,253.49
1993,Gas,79.32
1993,Elektrizität,170.06
1993,Übrige erneuerbare Energien,16.13
1994,Holz,28.4
1994,Kohle,7.35
1994,Industrieabfälle,10.11
1994,Erdölbrennstoffe,228.48
1994,Erdöltreibstoffe,257.47
1994,Gas,78.06
1994,Elektrizität,168.83
1994,Übrige erneuerbare Energien,16.07
1995,Holz,30.26
1995,Kohle,7.92
1995,Industrieabfälle,10.44
1995,Erdölbrennstoffe,237.68
1995,Erdöltreibstoffe,256.36
1995,Gas,86
1995,Elektrizität,172.38
1995,Übrige erneuerbare Energien,17.21
1996,Holz,33.29
1996,Kohle,5.96
1996,Industrieabfälle,11.11
1996,Erdölbrennstoffe,243.54
1996,Erdöltreibstoffe,259.08
1996,Gas,92.32
1996,Elektrizität,175.29
1996,Übrige erneuerbare Energien,18.22
1997,Holz,29.26
1997,Kohle,4.59
1997,Industrieabfälle,10.09
1997,Erdölbrennstoffe,228.1
1997,Erdöltreibstoffe,268.89
1997,Gas,88.55
1997,Elektrizität,175
1997,Übrige erneuerbare Energien,18.65
1998,Holz,29.74
1998,Kohle,3.81
1998,Industrieabfälle,10.32
1998,Erdölbrennstoffe,239.75
1998,Erdöltreibstoffe,274.46
1998,Gas,91.55
1998,Elektrizität,178.63
1998,Übrige erneuerbare Energien,19.3
1999,Holz,29.36
1999,Kohle,3.96
1999,Industrieabfälle,8.93
1999,Erdölbrennstoffe,227.68
1999,Erdöltreibstoffe,286.92
1999,Gas,92.84
1999,Elektrizität,184.37
1999,Übrige erneuerbare Energien,19.51
2000,Holz,27.63
2000,Kohle,5.77
2000,Industrieabfälle,10.44
2000,Erdölbrennstoffe,208.43
2000,Erdöltreibstoffe,293.37
2000,Gas,93.16
2000,Elektrizität,188.54
2000,Übrige erneuerbare Energien,19.51
2001,Holz,29.52
2001,Kohle,6.03
2001,Industrieabfälle,10.45
2001,Erdölbrennstoffe,226.75
2001,Erdöltreibstoffe,285.87
2001,Gas,97.02
2001,Elektrizität,193.5
2001,Übrige erneuerbare Energien,20.68
2002,Holz,28.22
2002,Kohle,5.56
2002,Industrieabfälle,10.19
2002,Erdölbrennstoffe,208.24
2002,Erdöltreibstoffe,279.81
2002,Gas,94.86
2002,Elektrizität,194.5
2002,Übrige erneuerbare Energien,20.95
2003,Holz,30.14
2003,Kohle,5.71
2003,Industrieabfälle,11.06
2003,Erdölbrennstoffe,218.43
2003,Erdöltreibstoffe,276.64
2003,Gas,99.98
2003,Elektrizität,198.44
2003,Übrige erneuerbare Energien,22.02
2004,Holz,29.9
2004,Kohle,5.42
2004,Industrieabfälle,10.98
2004,Erdölbrennstoffe,215.46
2004,Erdöltreibstoffe,275.42
2004,Gas,103.43
2004,Elektrizität,202.22
2004,Übrige erneuerbare Energien,22.56
2005,Holz,31.07
2005,Kohle,6.04
2005,Industrieabfälle,10.88
2005,Erdölbrennstoffe,215.72
2005,Erdöltreibstoffe,277.5
2005,Gas,106.46
2005,Elektrizität,206.39
2005,Übrige erneuerbare Energien,23.77
2006,Holz,31.49
2006,Kohle,6.52
2006,Industrieabfälle,10.99
2006,Erdölbrennstoffe,207.68
2006,Erdöltreibstoffe,281.3
2006,Gas,104.42
2006,Elektrizität,208.02
2006,Übrige erneuerbare Energien,24.69
2007,Holz,30.3
2007,Kohle,7.3
2007,Industrieabfälle,10.6
2007,Erdölbrennstoffe,180.73
2007,Erdöltreibstoffe,289.33
2007,Gas,102.18
2007,Elektrizität,206.76
2007,Übrige erneuerbare Energien,24.38
2008,Holz,33.76
2008,Kohle,6.56
2008,Industrieabfälle,11.13
2008,Erdölbrennstoffe,188.23
2008,Erdöltreibstoffe,298.42
2008,Gas,108.88
2008,Elektrizität,211.42
2008,Übrige erneuerbare Energien,26.67
2009,Holz,34.74
2009,Kohle,6.19
2009,Industrieabfälle,9.51
2009,Erdölbrennstoffe,182.08
2009,Erdöltreibstoffe,293.45
2009,Gas,104.53
2009,Elektrizität,206.98
2009,Übrige erneuerbare Energien,27.37
2010,Holz,37.99
2010,Kohle,6.21
2010,Industrieabfälle,10.04
2010,Erdölbrennstoffe,190.41
2010,Erdöltreibstoffe,295.08
2010,Gas,115.94
2010,Elektrizität,215.23
2010,Übrige erneuerbare Energien,31.54
2011,Holz,33.06
2011,Kohle,5.74
2011,Industrieabfälle,10.51
2011,Erdölbrennstoffe,150.85
2011,Erdöltreibstoffe,296.59
2011,Gas,104.21
2011,Elektrizität,210.96
2011,Übrige erneuerbare Energien,30.06
2012,Holz,36.47
2012,Kohle,5.17
2012,Industrieabfälle,10.3
2012,Erdölbrennstoffe,161.13
2012,Erdöltreibstoffe,299.85
2012,Gas,114.32
2012,Elektrizität,212.3
2012,Übrige erneuerbare Energien,33.19
2013,Holz,40.05
2013,Kohle,5.57
2013,Industrieabfälle,10.44
2013,Erdölbrennstoffe,168.46
2013,Erdöltreibstoffe,299.77
2013,Gas,120.75
2013,Elektrizität,213.56
2013,Übrige erneuerbare Energien,35.78
2014,Holz,33.94
2014,Kohle,5.7
2014,Industrieabfälle,11.83
2014,Erdölbrennstoffe,127.55
2014,Erdöltreibstoffe,298.26
2014,Gas,107.11
2014,Elektrizität,206.88
2014,Übrige erneuerbare Energien,33.73
2015,Holz,36.11
2015,Kohle,5.21
2015,Industrieabfälle,10.19
2015,Erdölbrennstoffe,133.89
2015,Erdöltreibstoffe,290.53
2015,Gas,112.93
2015,Elektrizität,209.69
2015,Übrige erneuerbare Energien,39.01
2016,Holz,38.98
2016,Kohle,4.79
2016,Industrieabfälle,10.79
2016,Erdölbrennstoffe,136.35
2016,Erdöltreibstoffe,291.82
2016,Gas,117.23
2016,Elektrizität,209.66
2016,Übrige erneuerbare Energien,43.28
2017,Holz,38.61
2017,Kohle,4.61
2017,Industrieabfälle,12.5
2017,Erdölbrennstoffe,127.93
2017,Erdöltreibstoffe,290.1
2017,Gas,118.9
2017,Elektrizität,210.54
2017,Übrige erneuerbare Energien,46.61
```



<hr /></section>

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesqueeu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo,fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut,imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputateeleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac,enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellusviverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiamultricies nisi vel augue.

<section><h6>DYNAMIC_COMPONENT</h6>

```
{
  "autoHtml": true,
  "props": {
    "item": {
      "color": "#fff",
      "date": "Von Urs Bruderer (Text) und Adam Higton (Illustrationen), 07.09.2018",
      "url": "https://www.republik.ch/2018/09/07/das-land-wo-bald-die-zitronen-bluehn",
      "textPosition": "topright",
      "title": "Das Land, wo bald die Zitronen blühn",
      "split": true,
      "type": "Beitrag",
      "image": "https://cdn.republik.space/s3/republik-assets/github/republik/article-das-land-wo-die-zitronen-bluehn/images/cf31077d21d1e2accace0240a3b004e3b631eb39.gif",
      "lead": "Die Schweiz wird zu einem mediterranen Land, nur leider ohne Meer. Für die Landwirtschaft ein Glück: Es werden Melonen, Reis und Topweine wachsen. Doch den Bauern fällt die Umstellung schwer, die der Klimawandel verlangt.",
      "bgColor": "#EFCE5A"
    }
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/banner.js?v10",
  "size": "breakout"
}
```

```html
<style>.css-1rozygh, [data-css-1rozygh] { display: block; width: 100%; }.css-bv4hie, [data-css-bv4hie] { margin: 10px 0px 0px; font-family: GT-America-Standard-Regular, "Helvetica Neue", Helvetica, sans-serif; font-size: 14px; line-height: 17px; color: rgb(40, 40, 40); }@media only screen and (min-width: 768px) {
  .css-bv4hie, [data-css-bv4hie] { font-family: GT-America-Standard-Regular, "Helvetica Neue", Helvetica, sans-serif; font-size: 15px; line-height: 21px; margin: 20px 0px 0px; }
}.css-avcph8 a, [data-css-avcph8] a { text-decoration: none; color: rgb(60, 173, 0); }.css-avcph8 a:visited, [data-css-avcph8] a:visited { color: rgb(60, 173, 0); }.css-avcph8 ul, [data-css-avcph8] ul, .css-avcph8 ol, [data-css-avcph8] ol { overflow: hidden; }@media (hover) {
  .css-avcph8 a:hover, [data-css-avcph8] a:hover { color: rgb(75, 99, 89); }
}@media only screen and (min-width: 1050px) {
  .css-1tqzily, [data-css-1tqzily] { margin-left: -170px; margin-right: -170px; width: calc(100% + 340px); }
}.css-13azwyo, [data-css-13azwyo] { position: relative; }.css-17du2v3, [data-css-17du2v3] { margin: 0px 0px 15px; }@media only screen and (min-width: 640px) {
  .css-17du2v3, [data-css-17du2v3] { margin-bottom: 30px; }
}.css-4ql49i, [data-css-4ql49i] { font-family: RepublikSerif-Black, Rubis-Bold, Georgia, serif; font-weight: 900; font-size: 58px; line-height: 60px; }.css-ypdpeg, [data-css-ypdpeg] { font-size: 38px; line-height: 43px; }@media only screen and (min-width: 640px) {
  .css-ypdpeg, [data-css-ypdpeg] { font-size: 58px; line-height: 60px; }
}@media only screen and (min-width: 1174px) {
  .css-ypdpeg, [data-css-ypdpeg] { font-size: 80px; line-height: 90px; }
}.css-4vuuf9, [data-css-4vuuf9] { margin: 0px; overflow: hidden; }@media only screen and (min-width: 640px) {
  .css-4vuuf9, [data-css-4vuuf9] { display: flex; padding: 70px 5%; -webkit-box-align: center; align-items: center; -webkit-box-pack: center; justify-content: center; }
}.css-1n95dyr, [data-css-1n95dyr] { padding: 15px 15px 40px; }@media only screen and (min-width: 640px) {
  .css-1n95dyr, [data-css-1n95dyr] { padding: 0px 0px 0px 5%; width: 50%; }
}.css-7moq6x, [data-css-7moq6x] { position: relative; }@media only screen and (min-width: 640px) {
  .css-7moq6x, [data-css-7moq6x] { font-size: 0px; height: auto; width: 50%; flex-shrink: 0; }
}.css-bnxy44, [data-css-bnxy44] { font-family: Rubis-Regular, Georgia, serif; font-size: 19px; line-height: 27px; margin: 0px 0px 10px; color: rgb(40, 40, 40); }@media only screen and (min-width: 640px) {
  .css-bnxy44, [data-css-bnxy44] { font-family: Rubis-Regular, Georgia, serif; font-size: 23px; line-height: 30px; margin: 0px 0px 20px; }
}.css-f1b3sd, [data-css-f1b3sd] { color: inherit; text-decoration: none; cursor: pointer; }.css-f1b3sd:visited, [data-css-f1b3sd]:visited { color: inherit; }.css-1aa4c3s a, [data-css-1aa4c3s] a { color: inherit; text-decoration: underline; }.css-1aa4c3s a:visited, [data-css-1aa4c3s] a:visited { color: inherit; }</style>
<div data-css-1tqzily=""><div data-css-4vuuf9="" style="background: rgb(239, 206, 90); cursor: default;"><div data-css-7moq6x=""><img data-css-1rozygh="" src="https://cdn.republik.space/s3/republik-assets/github/republik/article-das-land-wo-die-zitronen-bluehn/images/cf31077d21d1e2accace0240a3b004e3b631eb39.gif" alt=""></div><div data-css-1n95dyr=""><div><div data-css-13azwyo="" style="color: rgb(255, 255, 255);"><h1 data-css-17du2v3="" data-css-4ql49i="" data-css-ypdpeg=""><a data-css-f1b3sd="" href="https://www.republik.ch/2018/09/07/das-land-wo-bald-die-zitronen-bluehn">Das Land, wo bald die Zitronen blühn</a></h1><span data-css-bnxy44="" style="color: inherit;">Die Schweiz wird zu einem mediterranen Land, nur leider ohne Meer. Für die Landwirtschaft ein Glück: Es werden Melonen, Reis und Topweine wachsen. Doch den Bauern fällt die Umstellung schwer, die der Klimawandel verlangt.</span><p data-css-bv4hie="" style="color: inherit;"><div data-css-1aa4c3s=""><span data-css-avcph8=""></span></div></p></div></div></div></div></div>
```

<hr /></section>

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesqueeu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo,fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut,imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputateeleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac,enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellusviverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiamultricies nisi vel augue.

<section><h6>DYNAMIC_COMPONENT</h6>

```
{
  "autoHtml": true,
  "props": {
    "item": {
      "color": "#fff",
      "date": "Von Elia Blülle, 15.03.2019",
      "url": "https://www.republik.ch/2019/03/15/no-future-das-war-gestern",
      "title": "No future, das war gestern",
      "split": true,
      "type": "Beitrag",
      "image": "https://cdn.republik.space/s3/republik-assets/github/republik/article-aufstand-der-streber/images/bab62c96339c128d7e88d2288c92b7097b07deb8.jpeg",
      "lead": "Die Schweiz wird zu einem mediterranen Land, nur leider ohne Meer. Für die Landwirtschaft ein Glück: Es werden Melonen, Reis und Topweine wachsen. Doch den Bauern fällt die Umstellung schwer, die der Klimawandel verlangt.",
      "bgColor": "#47C8F0"
    }
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/banner.js?v10",
  "size": "breakout"
}
```

```html
<style>.css-1rozygh, [data-css-1rozygh] { display: block; width: 100%; }.css-bv4hie, [data-css-bv4hie] { margin: 10px 0px 0px; font-family: GT-America-Standard-Regular, "Helvetica Neue", Helvetica, sans-serif; font-size: 14px; line-height: 17px; color: rgb(40, 40, 40); }@media only screen and (min-width: 768px) {
  .css-bv4hie, [data-css-bv4hie] { font-family: GT-America-Standard-Regular, "Helvetica Neue", Helvetica, sans-serif; font-size: 15px; line-height: 21px; margin: 20px 0px 0px; }
}.css-avcph8 a, [data-css-avcph8] a { text-decoration: none; color: rgb(60, 173, 0); }.css-avcph8 a:visited, [data-css-avcph8] a:visited { color: rgb(60, 173, 0); }.css-avcph8 ul, [data-css-avcph8] ul, .css-avcph8 ol, [data-css-avcph8] ol { overflow: hidden; }@media (hover) {
  .css-avcph8 a:hover, [data-css-avcph8] a:hover { color: rgb(75, 99, 89); }
}@media only screen and (min-width: 1050px) {
  .css-1tqzily, [data-css-1tqzily] { margin-left: -170px; margin-right: -170px; width: calc(100% + 340px); }
}.css-13azwyo, [data-css-13azwyo] { position: relative; }.css-17du2v3, [data-css-17du2v3] { margin: 0px 0px 15px; }@media only screen and (min-width: 640px) {
  .css-17du2v3, [data-css-17du2v3] { margin-bottom: 30px; }
}.css-4ql49i, [data-css-4ql49i] { font-family: RepublikSerif-Black, Rubis-Bold, Georgia, serif; font-weight: 900; font-size: 58px; line-height: 60px; }.css-ypdpeg, [data-css-ypdpeg] { font-size: 38px; line-height: 43px; }@media only screen and (min-width: 640px) {
  .css-ypdpeg, [data-css-ypdpeg] { font-size: 58px; line-height: 60px; }
}@media only screen and (min-width: 1174px) {
  .css-ypdpeg, [data-css-ypdpeg] { font-size: 80px; line-height: 90px; }
}.css-4vuuf9, [data-css-4vuuf9] { margin: 0px; overflow: hidden; }@media only screen and (min-width: 640px) {
  .css-4vuuf9, [data-css-4vuuf9] { display: flex; padding: 70px 5%; -webkit-box-align: center; align-items: center; -webkit-box-pack: center; justify-content: center; }
}.css-1n95dyr, [data-css-1n95dyr] { padding: 15px 15px 40px; }@media only screen and (min-width: 640px) {
  .css-1n95dyr, [data-css-1n95dyr] { padding: 0px 0px 0px 5%; width: 50%; }
}.css-7moq6x, [data-css-7moq6x] { position: relative; }@media only screen and (min-width: 640px) {
  .css-7moq6x, [data-css-7moq6x] { font-size: 0px; height: auto; width: 50%; flex-shrink: 0; }
}.css-bnxy44, [data-css-bnxy44] { font-family: Rubis-Regular, Georgia, serif; font-size: 19px; line-height: 27px; margin: 0px 0px 10px; color: rgb(40, 40, 40); }@media only screen and (min-width: 640px) {
  .css-bnxy44, [data-css-bnxy44] { font-family: Rubis-Regular, Georgia, serif; font-size: 23px; line-height: 30px; margin: 0px 0px 20px; }
}.css-f1b3sd, [data-css-f1b3sd] { color: inherit; text-decoration: none; cursor: pointer; }.css-f1b3sd:visited, [data-css-f1b3sd]:visited { color: inherit; }.css-1aa4c3s a, [data-css-1aa4c3s] a { color: inherit; text-decoration: underline; }.css-1aa4c3s a:visited, [data-css-1aa4c3s] a:visited { color: inherit; }</style>
<div data-css-1tqzily=""><div data-css-4vuuf9="" style="background: rgb(71, 200, 240); cursor: default;"><div data-css-7moq6x=""><img data-css-1rozygh="" src="https://cdn.republik.space/s3/republik-assets/github/republik/article-aufstand-der-streber/images/bab62c96339c128d7e88d2288c92b7097b07deb8.jpeg" alt=""></div><div data-css-1n95dyr=""><div><div data-css-13azwyo="" style="color: rgb(255, 255, 255);"><h1 data-css-17du2v3="" data-css-4ql49i="" data-css-ypdpeg=""><a data-css-f1b3sd="" href="https://www.republik.ch/2019/03/15/no-future-das-war-gestern">No future, das war gestern</a></h1><span data-css-bnxy44="" style="color: inherit;">Die Schweiz wird zu einem mediterranen Land, nur leider ohne Meer. Für die Landwirtschaft ein Glück: Es werden Melonen, Reis und Topweine wachsen. Doch den Bauern fällt die Umstellung schwer, die der Klimawandel verlangt.</span><p data-css-bv4hie="" style="color: inherit;"><div data-css-1aa4c3s=""><span data-css-avcph8=""></span></div></p></div></div></div></div></div>
```

<hr /></section>

<section><h6>DYNAMIC_COMPONENT</h6>

```
{
  "autoHtml": false,
  "props": {
    "comments": {
      "label": "Aus den Debatten",
      "entries": [
        {
          "id": "d2219a4a-6fd3-42ec-affe-9ee73af037fc",
          "createdAt": "2019-03-16T14:01:17.118Z",
          "content": {
            "type": "root",
            "children": [
              {
                "type": "paragraph",
                "children": [
                  {
                    "type": "text",
                    "value": "Vielen Dank für diese "
                  },
                  {
                    "type": "strong",
                    "children": [
                      {
                        "type": "text",
                        "value": "umfassende Einordnung"
                      }
                    ]
                  },
                  {
                    "type": "text",
                    "value": " und Würdigung der Klimabewegung der Jugendlichen in der Schweiz und der Welt, Elia! Es gelingt dir, die "
                  },
                  {
                    "type": "strong",
                    "children": [
                      {
                        "type": "text",
                        "value": "Stärken der Bewegung"
                      }
                    ]
                  },
                  {
                    "type": "text",
                    "value": " zu zeigen, ohne sie zu verklären, du zeigst auf, warum man sie ernst nehmen kann und sollte,  bietest Ideen und Fragen an, die der Bewegung als Gedankenanstoss für eine "
                  },
                  {
                    "type": "strong",
                    "children": [
                      {
                        "type": "text",
                        "value": "erfolgreiche Weiterentwicklung"
                      }
                    ]
                  },
                  {
                    "type": "text",
                    "value": " dienen können und zeigst "
                  },
                  {
                    "type": "strong",
                    "children": [
                      {
                        "type": "text",
                        "value": "mögliche Absturzklippen"
                      }
                    ]
                  },
                  {
                    "type": "text",
                    "value": " auf. "
                  }
                ]
              },
              {
                "type": "paragraph",
                "children": [
                  {
                    "type": "text",
                    "value": "Der Titel irritierte mich erst, doch du löst ihn einleuchtend auf. "
                  }
                ]
              },
              {
                "type": "paragraph",
                "children": [
                  {
                    "type": "text",
                    "value": "Wäre das nicht ein Text, den ihr allen Schulleitungen, Schulbibliotheken und den euch bekannten Protagonistinnen der Bewegung zustellen könntet? (Eventuell auch allen Parlamentariern) —> als Einordnung, aber vor allem auch als Einladung, Verlegerinnen der Republik zu werden? "
                  }
                ]
              },
              {
                "type": "paragraph",
                "children": [
                  {
                    "type": "text",
                    "value": "Nochmals danke! Und "
                  },
                  {
                    "type": "strong",
                    "children": [
                      {
                        "type": "text",
                        "value": "speziellen Dank an die Bildredaktion"
                      }
                    ]
                  },
                  {
                    "type": "text",
                    "value": " für das Aufmacherbild. „Let’s make the earth cool again“ zeigt  schön, dass diese Bewegung auch mit Humor ans Werk geht, was erfrischend ist. "
                  }
                ]
              }
            ]
          },
          "displayAuthor": {
            "name": "Nadja Schnetzler",
            "profilePicture": "https://cdn.republik.space/s3/republik-assets/portraits/4c27f1ee3b331c07f106956085b27034.jpeg?size=5212x3468&resize=384x384&bw=true"
          },
          "preview": {
            "string": "Vielen Dank für diese umfassende Einordnung und Würdigung der Klimabewegung der Jugendlichen in der Schweiz und der Welt, Elia! Es gelingt dir, die Stärken der Bewegung zu zeigen, ohne sie zu verklären, du zeigst auf, warum man sie ernst nehmen kann und sollte, bietest Ideen und Fragen an, die der Bewegung als Gedankenanstoss für eine erfolgreiche Weiterentwicklung dienen können und zeigst mögliche Absturzklippen auf. Der Titel irritierte mich erst, doch du löst ihn einleuchtend auf. Wäre das",
            "more": true
          },
          "discussion": {
            "id": "240280a7-d8f5-4332-a7b4-8c768bb70ec4",
            "title": "Fordern können alle. Aber wer muss handeln?"
          }
        },
        {
          "id": "89b1aa3c-a4d0-4963-ad83-f338b2148fe5",
          "createdAt": "2019-03-16T14:01:17.118Z",
          "content": {
            "type": "root",
            "children": [
              {
                "type": "paragraph",
                "children": [
                  {
                    "type": "text",
                    "value": "Am Freitag nahm ich an der Klimastreikdemo in Zürich teil und war begeistert von diesem Engagement der jungen Menschen. Trotz orkanmässigem Wetter waren es abertausende motivierte Demonstrierende. Meine Begeisterung habe ich dann auch auf sozialen Medien geteilt und war erstaunt, welch kritische Bemerkungen es gab. Da wurde debattiert, dass die jungen Menschen selber, ein nicht umweltgerechtes Konsumverhalten hätten und dass nach den Demos Abfallberge zurückgelassen wurden. Es kursiert denn auch ein Bild in den sozialen Medien, das wenige Pappschilder neben einem überfüllten Abfalleimer zeigt. Ich habe weder auf der ETH-Polyterrasse noch später in der Stadt solche nAbfall gesehen und falls doch irgendwo ein paar Pappschilder nicht richtig entsorgt wurden, ist das wirklich ein Grund an den Motiven der Bewegung zu zweifeln? Ich habe grosse Hoffnung in diese Bewegung! Und möchte mich für das grosse Engagement bedanken, für unsere alle Zukunft. "
                  }
                ]
              }
            ]
          },
          "displayAuthor": {
            "name": "Daniel Peter",
            "profilePicture": null
          },
          "preview": {
            "string": "Am Freitag nahm ich an der Klimastreikdemo in Zürich teil und war begeistert von diesem Engagement der jungen Menschen. Trotz orkanmässigem Wetter waren es abertausende motivierte Demonstrierende. Meine Begeisterung habe ich dann auch auf sozialen Medien geteilt und war erstaunt, welch kritische Bemerkungen es gab. Da wurde debattiert, dass die jungen Menschen selber, ein nicht umweltgerechtes Konsumverhalten hätten und dass nach den Demos Abfallberge zurückgelassen wurden. Es kursiert denn auch",
            "more": true
          },
          "discussion": {
            "id": "240280a7-d8f5-4332-a7b4-8c768bb70ec4",
            "title": "Fordern können alle. Aber wer muss handeln?"
          }
        },
        {
          "id": "1dfb0e2b-bb3a-445c-b7b2-98e7824c736b",
          "createdAt": "2019-03-16T14:01:17.118Z",
          "content": {
            "type": "root",
            "children": [
              {
                "type": "paragraph",
                "children": [
                  {
                    "type": "text",
                    "value": "Das Klima und die Klimapolitik bewegt die Jungend. Das ist gut so! Dies sage ich auch als Freisinniger, der viele Ideen, welche aus dieser Jungendbewegung kommen, sehr kritisch sieht. Dass wir – jeder Einzelne, die Politik, die Schweiz, ja die ganze Welt – etwas tun müssen, steht für mich ausser Frage. Um zu diesem Schluss zukommen, muss man nicht Klimawissenschaftler sein. Nicht nur die IPCC-Berichte sind eindeutig. Auch die Entwicklungen der letzten 20 Jahre zeigen: Der Klimawandel ist Realität. Dass der Mensch dabei eine (zentrale) Rolle spielt, ist anhand der wissenschaftlichen Erkenntnisse eben so klar. Nun kommen wir zur Frage, was gilt es zu tun? Anders als bei den wissenschaftlichen Erkenntnissen gibt es darauf keine eindeutige Antwort. Bekanntlich führen viele Wege nach Rom. Und so ist es auch hier! Viele Massnahmen, welche heute in der Politik und den Medien diskutiert werden, sind nichts anderes als staatliche Verbote oder massive Einschränkungen für Wirtschaft und Gesellschaft. Als liberaler Mensch stört mich das. Dass es auch andere Ansätze gibt, wird leider sehr oft vergessen."
                  },
                  {
                    "type": "break"
                  },
                  {
                    "type": "text",
                    "value": "Um Ihnen diese anderen Ansätze etwas näher zu bringen, muss ich zuerst etwas ausholen. Das Klimaproblem stellt aus ökonomischer Sicht ein Marktversagen dar. Dieses Marktversagen kommt deshalb zustande, weil bei der Luft anders als beim Boden, Kapital, etc. eine Zuteilung der Eigentumsrechte fehlt. Illustrieren lässt sich dies anhand eines Beispiels: Will ich ein Haus bauen, brauche ich ein Stück Land. Das Stück Land muss mir gehören, ansonsten kann ich kein Haus bauen. Bei der Luft ist dies anders. Sie gehört niemandem. Auch dem Staat nicht. Sie ist ein öffentliches Gut. Ich kann die Luft jederzeit und überall nutzen und brauche dazu kein Recht – sie muss mir nicht «gehören». Dies führt dazu, dass jedermann die Luft gratis verschmutzen kann. Wie lösen wir ein solches Problem aus ökonomischer und liberaler Sicht am besten? Nicht mit Verboten oder Steuern, sondern in dem der Staat bzw. die Staaten Gemeinschaft des Pariser Abkommens das Marktversagen durch die Schaffung eines Marktes für Verschmutzungsrechte löst. Nur wer ein entsprechendes Verschmutzungsrecht besitzt, darf die Luft entsprechend belasten. Die Anzahl der Verschmutzungsrechte sollte sich dabei an den Zielen des Pariser Abkommens orientieren. Um eine gewisse Sozialverträglichkeit zu gewährleisten, sollte eine Art Grundbedarf kostenlos an die Bürger verteilt werden. Die GLP wird nun fragen, wieso ein verbindlicher Markt für Verschmutzungsrechte anstatt einer CO2-Lenkungsabgabe. Das Problem an der CO2-Abgabe: Wir kennen den Preis nicht, welchen es braucht um die Ziele des Pariser Abkommens zu erreichen. Der Staat müsste dauernd Anmassung von Wissen betreiben. Beim Markt für Verschmutzungsrechte nutzen wir die Stärken des Marktes um die Ziele kostengünstig und effizient zu erreichen."
                  }
                ]
              }
            ]
          },
          "displayAuthor": {
            "name": "Alain Schwald",
            "profilePicture": null
          },
          "discussion": {
            "id": "240280a7-d8f5-4332-a7b4-8c768bb70ec4",
            "title": "Fordern können alle. Aber wer muss handeln?"
          },
          "preview": {
            "string": "Das Klima und die Klimapolitik bewegt die Jungend. Das ist gut so! Dies sage ich auch als Freisinniger, der viele Ideen, welche aus dieser Jungendbewegung kommen, sehr kritisch sieht. Dass wir – jeder Einzelne, die Politik, die Schweiz, ja die ganze Welt – etwas tun müssen, steht für mich ausser Frage. Um zu diesem Schluss zukommen, muss man nicht Klimawissenschaftler sein. Nicht nur die IPCC-Berichte sind eindeutig. Auch die Entwicklungen der letzten 20 Jahre zeigen: Der Klimawandel ist",
            "more": true
          }
        }
      ]
    },
    "press": {
      "label": "Das Beste der anderen",
      "entries": [
        {
          "source": "Neue Zürcher Zeitung",
          "url": "https://www.nzz.ch/1234",
          "quote": "Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus.",
          "date": "2017-11-21"
        },
        {
          "source": "New York Times",
          "url": "https://www.weltwoche",
          "quote": "Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus.",
          "date": "2017-11-21"
        },
        {
          "source": "New York Times",
          "url": "https://www.weltwoche",
          "quote": "Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus.",
          "date": "2017-11-21"
        }
      ]
    }
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/quotes.js?v7"
}
```

<hr /></section>

<section><h6>INFOBOX</h6>

### Über das Dossier «Klimawandel»

Das Thema ist uns wichtig. Hier sagen wir warum. Zudem veröffentlichen wir Links zu Daten und Methoden.

<hr /></section>



<hr /></section>
