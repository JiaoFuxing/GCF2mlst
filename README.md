# GCF2mlst
根据NCBI公共数据基因组的Accession，查询对应物种的MLST型。

## 安装/Install
```bash
git clone https://github.com/JiaoFuxing/GCF2mlst
conda env create -f env.yaml
conda activate GCF2mlst
```
## 运行示例/Run
```bash
./GCF2mlst-SingleStrain   ecoli  result  GCF_002233455.1 
./GCF2mlst-MutipleStrain  ecoli  result  /DFlab/Accession.list
(script  MLST_Species  output_file  Accession)
```
# By：Jacky14
