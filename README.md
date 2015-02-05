Experiment Code for RTB Feedback Control Techniques
===========

This is a repository of the experiment code supporting the paper "Feedback Control of Real-Time Display Advertising" submitted to KDD 2015.

For any problems, please report the issues here or contact [Weinan Zhang](http://www0.cs.ucl.ac.uk/staff/w.zhang/).

After pulling the repositoty, you could start from checking the demo under the folder of `scripts` by running:
```
$ bash run_demo_example.sh
```
You should get the following experiment results:
```
Example of PID control eCPC.
Data sample from campaign 1458 from iPinYou dataset.
Reference eCPC: 40000
test performance:
round	ecpc	phi	total_click	click_ratio	win_ratio	total_cost	ref
0	54062.0000	0.0000	2	0.0308	0.0250	162186.0000	40000.0
1	54230.3333	-2.0000	2	0.0308	0.0251	162691.0000	40000.0
2	40755.2500	-2.0000	3	0.0462	0.0254	163021.0000	40000.0
3	41001.7500	-0.9473	3	0.0462	0.0260	164007.0000	40000.0
4	41106.7500	-2.0000	3	0.0462	0.0264	164427.0000	40000.0
5	41185.0000	-2.0000	3	0.0462	0.0267	164740.0000	40000.0
6	41264.2500	-2.0000	3	0.0462	0.0270	165057.0000	40000.0
7	41281.7500	-2.0000	3	0.0462	0.0271	165127.0000	40000.0
8	41333.0000	-2.0000	3	0.0462	0.0272	165332.0000	40000.0
9	41399.7500	-2.0000	3	0.0462	0.0274	165599.0000	40000.0
10	41516.0000	-2.0000	3	0.0462	0.0277	166064.0000	40000.0
11	41589.5000	-2.0000	3	0.0462	0.0279	166358.0000	40000.0
12	33395.0000	-2.0000	4	0.0615	0.0281	166975.0000	40000.0
13	36367.7778	5.0000	8	0.1231	0.0524	327310.0000	40000.0
14	53518.5556	5.0000	8	0.1231	0.0769	481667.0000	40000.0
15	53540.1111	-2.0000	8	0.1231	0.0770	481861.0000	40000.0
16	53577.4444	-2.0000	8	0.1231	0.0770	482197.0000	40000.0
17	53615.3333	-2.0000	8	0.1231	0.0774	482538.0000	40000.0
18	53668.6667	-2.0000	8	0.1231	0.0777	483018.0000	40000.0
19	48342.4000	-2.0000	9	0.1385	0.0778	483424.0000	40000.0
20	48390.5000	-2.0000	9	0.1385	0.0781	483905.0000	40000.0
21	48407.5000	-2.0000	9	0.1385	0.0782	484075.0000	40000.0
22	48452.8000	-2.0000	9	0.1385	0.0784	484528.0000	40000.0
23	48460.8000	-2.0000	9	0.1385	0.0785	484608.0000	40000.0
24	48474.6000	-2.0000	9	0.1385	0.0788	484746.0000	40000.0
25	48512.5000	-2.0000	9	0.1385	0.0791	485125.0000	40000.0
26	48545.4000	-2.0000	9	0.1385	0.0795	485454.0000	40000.0
27	44195.7273	-2.0000	10	0.1538	0.0797	486153.0000	40000.0
28	44217.6364	-2.0000	10	0.1538	0.0800	486394.0000	40000.0
29	44244.6364	-2.0000	10	0.1538	0.0802	486691.0000	40000.0
30	44261.5455	-2.0000	10	0.1538	0.0804	486877.0000	40000.0
31	40599.1667	-2.0000	11	0.1692	0.0808	487190.0000	40000.0
32	40632.7500	-1.6148	11	0.1692	0.0812	487593.0000	40000.0
33	37527.4615	-2.0000	12	0.1846	0.0815	487857.0000	40000.0
34	39631.8750	5.0000	15	0.2308	0.1061	634110.0000	40000.0
35	36986.2222	0.7126	17	0.2615	0.1158	665752.0000	40000.0
36	42932.7895	5.0000	18	0.2769	0.1404	815723.0000	40000.0
37	42946.1053	-2.0000	18	0.2769	0.1406	815976.0000	40000.0
38	42977.7895	-2.0000	18	0.2769	0.1410	816578.0000	40000.0
39	42991.6842	-2.0000	18	0.2769	0.1412	816842.0000	40000.0

train performance:
round	ecpc	phi	total_click	click_ratio	win_ratio	total_cost	ref
0	39157.0000	0.0000	3	0.0380	0.0250	156628.0000	40000.0
1	70105.5000	2.5298	3	0.0380	0.0466	280422.0000	40000.0
2	70218.0000	-2.0000	3	0.0380	0.0469	280872.0000	40000.0
3	70272.0000	-2.0000	3	0.0380	0.0471	281088.0000	40000.0
4	70407.5000	-2.0000	3	0.0380	0.0473	281630.0000	40000.0
5	56395.4000	-2.0000	4	0.0506	0.0476	281977.0000	40000.0
6	56452.2000	-2.0000	4	0.0506	0.0479	282261.0000	40000.0
7	56565.6000	-2.0000	4	0.0506	0.0483	282828.0000	40000.0
8	56622.4000	-2.0000	4	0.0506	0.0488	283112.0000	40000.0
9	47254.1667	-2.0000	5	0.0633	0.0493	283525.0000	40000.0
10	47338.0000	-2.0000	5	0.0633	0.0500	284028.0000	40000.0
11	47438.3333	-2.0000	5	0.0633	0.0507	284630.0000	40000.0
12	47522.1667	-2.0000	5	0.0633	0.0512	285133.0000	40000.0
13	47555.1667	-2.0000	5	0.0633	0.0515	285331.0000	40000.0
14	40905.0000	-2.0000	6	0.0759	0.0518	286335.0000	40000.0
15	35855.6250	-2.0000	7	0.0886	0.0522	286845.0000	40000.0
16	44247.5000	5.0000	9	0.1139	0.0769	442475.0000	40000.0
17	44284.4000	-2.0000	9	0.1139	0.0773	442844.0000	40000.0
18	44324.8000	-2.0000	9	0.1139	0.0778	443248.0000	40000.0
19	44388.1000	-2.0000	9	0.1139	0.0785	443881.0000	40000.0
20	44461.0000	-2.0000	9	0.1139	0.0791	444610.0000	40000.0
21	40457.0000	-2.0000	10	0.1266	0.0794	445027.0000	40000.0
22	40548.9091	-1.2128	10	0.1266	0.0806	446038.0000	40000.0
23	40585.9091	-1.8987	10	0.1266	0.0810	446445.0000	40000.0
24	40608.1818	-2.0000	10	0.1266	0.0814	446690.0000	40000.0
25	40641.0000	-2.0000	10	0.1266	0.0819	447051.0000	40000.0
26	40692.8182	-2.0000	10	0.1266	0.0823	447621.0000	40000.0
27	40698.8182	-2.0000	10	0.1266	0.0824	447687.0000	40000.0
28	40714.5455	-2.0000	10	0.1266	0.0826	447860.0000	40000.0
29	40768.9091	-2.0000	10	0.1266	0.0829	448458.0000	40000.0
30	40802.3636	-2.0000	10	0.1266	0.0832	448826.0000	40000.0
31	40826.0000	-2.0000	10	0.1266	0.0834	449086.0000	40000.0
32	40850.1818	-2.0000	10	0.1266	0.0837	449352.0000	40000.0
33	40870.7273	-2.0000	10	0.1266	0.0841	449578.0000	40000.0
34	40897.5455	-2.0000	10	0.1266	0.0843	449873.0000	40000.0
35	40938.5455	-2.0000	10	0.1266	0.0846	450324.0000	40000.0
36	40967.6364	-2.0000	10	0.1266	0.0849	450644.0000	40000.0
37	41033.8182	-2.0000	10	0.1266	0.0851	451372.0000	40000.0
38	37634.8333	-2.0000	11	0.1392	0.0852	451618.0000	40000.0
39	40867.3333	5.0000	14	0.1772	0.1099	613010.0000	40000.0

```
This is a demo of controlling eCPC to 400,000 (RMB cent in CPM) by PID controller. The example data files `exp-data/train.txt` and `exp-data/test.txt` are sampled from the campaign 1458 from iPinYou dataset.

### Feature Engineering Code
By running more experiments, you will rely on another repository which is written for iPinYou dataset feature engineering.

Please check our GitHub project [make-ipinyou-data](https://github.com/wnzhang/make-ipinyou-data). After downloading the dataset, by simplying `make all` you can generate the standardised data which will be used in the bid optimisation tasks.
