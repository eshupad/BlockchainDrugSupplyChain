# BlockchainDrugSupplyChain

India  is  expected  to  become  the  world’s  largest  high-qualitydrugs   supplier   and   the pharmaceutical sector aims to grow in value to US$120-130 billion by 2030, from the current US$38 billion. The turnover of the domestic pharmaceutical market reached US$18.12 billion in 2018, growing 9.4% year-on-year. In February 2019, that statistic went up to 10%. The  Drug  Supply  Chain  is  the  means  through  which  medicines  are  delivered  from  the production  unitsto  the  end-user/consumer.  This  study  will  focus  on  the  B2B  aspects  of  the chain, thereby not considering the patients in the chain –only the fully equipped hospitals, as these institutions are the major aggregators of the drug type in consideration i.e. Critical Drugs.While the industry’s growth trajectory looks promising on the surface, it is evident that there is a significant gap between the strategic vision and operational realities of the sector. Indian pharmaceutical  companies  are  facing  a  unique set  of  challenges  that  are  creating  significant pressure on them to transform their supply chains. The Temperature sensitive nature of these exclusive drugs requires a thorough Cold Storage system in place. Any unreliable means of transport poses a major threat to the effectiveness of the drug itself. Major Pharmaceutical conglomerates also incentivize the Wholesalers/Stockists to  keep  a  large  inventory  of  their  products  at  a  relatively  low  risk.  This  leads  to  large  scale wastage of the drugs, due to the cost of the Claims made by the Wholesalers when returning the expired medicines. The final cost is borne by the consumer, which is highly undesirable. Hence,  this  undesirable  reverse  logistics  needs  to  be  reduced in  this  supply  chain  for  better utilization of the produce and cheaper medicines for the aggrieved party, i.e. the patients.Blockchain  can  potentially  provide  real  time  information  about  the  inventory  status  of  the drugs.  A  private  version  of  the  Blockchain  can  be  employed  to  ensure  that  the  Blockchain provides security features to the supply chain while ensuring that the Enterprise retains control of the flow and access of information in the lower levels of the chain.

In this study, we are focusing on privately operated Pharmaceutical companies and their supply chain. We focus on the ‘last mile’ delivery of Critical drugs, and how we can optimize the current supply chain to reduce the final cost borne by the patient.


# Installing Hyperledger Fabric v1.4 on Ubuntu 18.04 LTS

https://www.uniwebb.com/blog/post/how-to-install-hyperledger-fabric-14-on-ubuntu-1804-lts/1766/


# Installing Hyperledger Composer on Ubuntu 18.04 LTS

https://hyperledger.github.io/composer/latest/installing/installing-index


# Running the application

composer archive create -t dir -n .

composer network install --card PeerAdmin@hlfv1 --archiveFile mt@0.0.1.bna

composer network start --card PeerAdmin@hlfv1 --networkAdmin admin --networkAdminEnrollSecret adminpw --file networkadmin.card --networkName mt --networkVersion 0.0.1

composer card import --file networkadmin.card

composer network ping --card admin@mt

composer-rest-server

cd DrugTrack

npm run

REST Server hosted on localhost:3000
Angular App hosted on localhost:4200

