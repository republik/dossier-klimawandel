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
  "size": "breakout",
  "color": "label",
  "xTicks": [
    1960,
    1970,
    1980,
    1990,
    2000,
    2010,
    2017
  ]
}
```

### Jährlicher CO₂-Ausstoss

Millionen Tonnen

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

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligulaeget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturientmontes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesqueeu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo,fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut,imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputateeleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac,enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellusviverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiamultricies nisi vel augue.

<section><h6>ARTICLECOLLECTION</h6>

```
{
  "membersOnly": true,
  "unauthorizedText": ""
}
```

## Wissenschaftsgeschichte des Klimawandels

<section><h6>TEASERGROUP</h6>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-klima-forschungsgeschichte-teil-1?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "rE8idYdye",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

![](images/3b0bf2756d10cc922b0fa98cdcc37107040d1764.jpeg?size=3800x2850)

###### 

# Geheimnisvolle Strahlen

## Teil 1

#### Wie Forscher im 19. Jahrhundert die Erdwärme untersuchten und dabei den Treibhauseffekt entdeckten.

Von [Arian Bastani](/~5d99ec6e-cb7d-4b27-8bf9-375b61e7ea7e "Arian Bastani") (Text) und Kwennie Cheng (Illustration), 05.12.2018

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-geschichte-der-klimaforschung-teil-2?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "t68osCCEv",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

![](images/049475e84dddd6ccf8a3e174cf651c1f9260af69.jpeg?size=2500x1875)

###### 

# Der Klima-Code

## Teil 2

#### Wie der globale Temperaturanstieg von der blossen Theorie zur messbaren Realität wurde.

Von [Arian Bastani](/~5d99ec6e-cb7d-4b27-8bf9-375b61e7ea7e "Arian Bastani") (Text) und Kwennie Cheng (Illustration), 11.12.2018

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-geschichte-der-klimaforschung-teil-3?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "d6XSkJo35",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

![](images/8fa330d5231800457a6515a14e5851e7b9c720d8.jpeg?size=2500x1875)

###### 

# Tödliches Tauwetter

## Teil 3

#### Wie herauskam, dass das Klima sehr empfindlich auf ein kleines bisschen Gas reagiert.

Von [Arian Bastani](/~5d99ec6e-cb7d-4b27-8bf9-375b61e7ea7e "Arian Bastani") (Text) und Kwennie Cheng (Illustration), 17.12.2018

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-geschichte-der-klimaforschung-teil-4?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "YpGzUVa6y",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

![](images/96228f733ead89b147f9138a5cb9ee909031b679.jpeg?size=2500x1875)

###### 

# Kampf um die Wahrheit

## Teil 4

#### Wie die Klimaforschung den Weg in die Politik fand – und dort von mächtigen Gegnern bekämpft wurde.

Von [Arian Bastani](/~5d99ec6e-cb7d-4b27-8bf9-375b61e7ea7e "Arian Bastani") (Text) und Kwennie Cheng (Illustration), 27.12.2018

<hr /></section>

<hr /></section>

<hr /></section>

<section><h6>INFOBOX</h6>

### Über das Dossier «Klimawandel»

Das Thema ist uns wichtig. Hier sagen wir warum. Zudem veröffentlichen wir Links zu Daten und Methoden.

<hr /></section>



<hr /></section>
