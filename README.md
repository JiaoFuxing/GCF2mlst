#GCF2mlst
根据公共数据的biosample，查询对应物种的MLST型
#Install
git clone https://github.com/JiaoFuxing/GCF2mlst
conda env create -f env.yaml
conda activate GCF2mlst
#Run
./GCF2mlst-SingleStrain   ecoli  result  GCF_002233455.1 
./GCF2mlst-MutipleStrain  ecoli  result  /DFlab/Accession.list
(script  MLST_Species  output_file  Accession)

By：Jacky14