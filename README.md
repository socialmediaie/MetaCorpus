# MetaCorpus
A meta corpus of social media corpus. Part of the [SocialMediaIE Project](http://socialmediaie.github.io). 

- [MetaCorpus](#metacorpus)
  * [Twitter](#twitter)
    + [Classification](#classification)
    + [Stance detection](#stance-detection)
    + [Tagging](#tagging)
      - [NER datasets](#ner-datasets)
    + [Entity Linking](#entity-linking)
    + [Machine Translation](#machine-translation)
    + [Paraphrase identification](#paraphrase-identification)
    + [Rumour detection](#rumour-detection)
    + [Treebank and parsing](#treebank-and-parsing)
    + [Question answering](#question-answering)
    + [Conversations](#conversations)
    + [Information Retrieval](#information-retrieval)
    + [Multimodal](#multimodal)
    + [Sentence Similarity](#sentence-similarity)
    + [Summarization](#summarization)
    + [General](#general)
    + [Tools, Tips, and Tricks](#tools--tips--and-tricks)
    + [Embeddings](#embeddings)
    + [Unlabled topic specific data dumps](#unlabled-topic-specific-data-dumps)
  * [Facebook](#facebook)
    + [Classification](#classification-1)
  * [Youtube:](#youtube-)
    + [Classification](#classification-2)
    + [Videos](#videos)
    + [General](#general-1)
  * [Reddit](#reddit)
    + [Classification](#classification-3)
    + [Summarization](#summarization-1)
    + [Sequence Tagging](#sequence-tagging)
    + [Named Entitis](#named-entitis)
    + [Conversations](#conversations-1)
    + [Tools](#tools)
  * [Gab](#gab)
    + [Summarization](#summarization-2)
    + [Amazon](#amazon)
  * [About.me](#aboutme)
  * [Whatsapp](#whatsapp)
  * [Delicious](#delicious)
  * [Ask.fm](#askfm)
  * [Flickr](#flickr)
    + [Popularity prediction](#popularity-prediction)
  * [Conversations](#conversations-2)
  * [News Comments](#news-comments)
  * [Weibo](#weibo)
  * [Whisper](#whisper)
  * [SMS](#sms)
  * [General](#general-2)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>



## Twitter


### Classification
* Hate and abusive speech - https://github.com/ENCASEH2020/hatespeech-twitter
* HateEval (SemEval 2019) - https://github.com/cicl2018/HateEvalTeam
* Aggregation identification - https://github.com/SilentFlame/AggressionDetection
* Hate speech ICWSM 2017 - https://github.com/t-davidson/hate-speech-and-offensive-language
* Moral Foundations Twitter Corpus - https://psyarxiv.com/w4f72 [\[JSON data\]](https://osf.io/k5n7y/)
* Vulgarity prediction on tweets - https://github.com/ericholgate/vulgartwitter
* CrisisNLP - http://crisisnlp.qcri.org
* CrisisLex - http://crisislex.org
* CREDBANK - credible events for tweets - http://compsocial.github.io/CREDBANK-data/
* Social roles in Twitter - https://data.csiro.au/dap/landingpage?pid=csiro:33845
* Biomedical entities in tweets - http://diego.asu.edu/Publications/ADRMine.html
* UK election sentiment - https://figshare.com/articles/EACL_2017_-_Multi-target_UK_election_Twitter_sentiment_corpus/4479563
* Novelty Detection in Tweets - https://github.com/CrowdTruth/Novelty_Detection [Project Page](http://data.crowdtruth.org/salience-news-tweets/)
* MovieTweetings - https://github.com/sidooms/MovieTweetings
* Monthly twitter Archive by the Internet Archive team from 2012-2018 - https://archive.org/details/twitterstream?&sort=-date&page=1
* [EmoContext](https://www.humanizing-ai.com/emocontext.html) dataset archived at Wayback Machine - [Train](https://web.archive.org/web/20190225030315/https://emocontext.blob.core.windows.net/data/starterkitdata.zip), [Dev](https://web.archive.org/web/20190225030352/https://emocontext.blob.core.windows.net/data/devsetwithlabels.zip), [Test](https://web.archive.org/web/20190225030419/https://emocontext.blob.core.windows.net/data/test.zip)
* Multi target sentiment - https://github.com/bluemonk482/tdparse
* [RumourEval 2019](https://competitions.codalab.org/competitions/19938#participate) [Data](https://figshare.com/articles/dataset/RumourEval_2019_data/8845580)
* [Sentiment, Emotion, Purpose, and Style in Electoral Tweets and Semantic Role Labeling of Emotions in Tweets](http://saifmohammad.com/WebDocs/ElectoralTweetsData.zip)
* [Hashtag Emotion Corpus (aka Twitter Emotion Corpus, or TEC)](http://saifmohammad.com/WebDocs/Jan9-2012-tweets-clean.txt.zip)
* List of sentiment corpora: https://www.w3.org/community/sentiment/wiki/Datasets
* Code Mixing and POS between English, Hindi, Bengali, and Telgu for FB, Twitter, and Whatsapp: http://www.amitavadas.com/Code-Mixing.html
* Twitter topic communities: https://github.com/uwnlp/twittercommunities
* Many useful datasets by Arkaitz Zubiaga: http://www.zubiaga.org/datasets/
* Twitter Optimism Dataset - http://lit.eecs.umich.edu/downloads.html#Twitter%20Optimism%20Dataset
* Grounded Emotions - http://web.eecs.umich.edu/~mihalcea/downloads/GroundedEmotions.tar.gz
* Vulgar tweet dataset - https://github.com/ericholgate/VulgarFunctionsTwitter/blob/master/Vulgar_Functions_Dataset.tsv
* Misogynistic tweet classification in Italian and English - https://amievalita2018.wordpress.com/
* Hatespeech detection on Facebook and Twitter (Italian) - http://www.di.unito.it/~tutreeb/haspeede-evalita18/index.html
* How to build a twitter archive - https://arxiv.org/abs/1611.08144
* Internet Archive twitter stream - https://archive.org/details/twitterstream
* Twitter datasets collected for specific events, e.g. US elections, has doi for each - https://tweetsets.library.gwu.edu/
* Tweets tagged with geolocations in geonames - https://github.com/geovista/GeoCorpora/blob/master/geocorpora_1544784178012.tsv
* Tweet geolocation datasets - https://github.com/afshinrahimi/geographconv
* Tweets tagged pro versus anti vaccine - http://www.cs.jhu.edu/~mdredze/data/
* Twitter Firstname, Lastname clusters - http://www.clsp.jhu.edu/~sbergsma/TwitterClusters/ (can be used for name location prediction)
* Twitter user level datasets for political ideologies - http://www.preotiuc.ro/resources.html
* A collection of tweet datasets - https://data.world/datasets/twitter
* End of Term 2016 U.S. Government Twitter Archive - https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/TQBLWZ
* Factuality of tweets - https://github.com/jacobeisenstein/twitter-certainty
* Parallel data for Machine Translation from tweets - http://www.cs.cmu.edu/~lingwang/microtopia/#translation
* Tweet to news linked corpora - http://www.cs.columbia.edu/~weiwei/code/acl2013.zip Source: http://www.cs.columbia.edu/~weiwei/code.html
* Congressional tweets labeled for frames and issues - https://github.com/kmjohnson/twitter-framing 
    - train test splits can be used from https://github.com/coastalcph/issue_framing/tree/master/data/congressional_tweets 
    - Same data labeled for moral foundations labels - https://github.com/kmjohnson/twitter-morals
* Presidential candidate tweets labeled for issues - https://github.com/kmjohnson/political-twitter
* Daily update of US congress politician tweets - https://github.com/alexlitel/congresstweets/tree/master/data
* Salience in News Tweets - http://data.crowdtruth.org/salience-news-tweets/ https://zenodo.org/record/46477
* Routinely collected Tweets datasets on topics of importance in US (esp US political tweets) - https://www.docnow.io/catalog/
* Twitter Cascades data - https://zenodo.org/record/2585375#.XVrLIOhKh3g
* Twitter News dataset - https://users.dcc.uchile.cl/~mquezada/breakingnews/
* 30 events dataset - https://figshare.com/articles/Twitter_event_datasets_2012-2016_/5100460
* Open Knowledge Representation for twitter events - http://u.cs.biu.ac.il/~nlp/resources/downloads/twitter-events/
* All verified Twitter users - https://www.reddit.com/r/datasets/comments/8s6nqz/all_verified_twitter_users_100_complete_in_ndjson/
* Many twitter datasets by pushshift - https://files.pushshift.io/
* Real time trending topic classification - http://nlp.uned.es/~damiano/datasets/TT-classification.html
* Balancing information exposure in social networks - https://github.com/gvrkiran/BalancedExposure - https://users.ics.aalto.fi/kiran/BalanceExposure/
* Online public shaming - https://zenodo.org/record/2587843#.XVrXzOhKh3g
* Abusive behavior - https://zenodo.org/record/1216127#.XVriSehKh3g
* GermEval offence evaluation task - https://projects.fzai.h-da.de/iggsa/projekt/	
* GermEval-2018-Data - https://github.com/uds-lsv/GermEval-2018-Data * OffenseEval - https://competitions.codalab.org/competitions/20011
* Frame Semantics Twitter (AAAI 2015) - https://bitbucket.org/lowlands/release/src/master/AAAI15/ (Paper: https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9349)
* SemEval 2017 dataset [Gold](https://www.dropbox.com/s/byzr8yoda6bua1b/2017_English_final.zip) - [Task Download](http://alt.qcri.org/semeval2017/task4/index.php?id=download-the-full-training-data-for-semeval-2017-task-4)
* MTSA - Multiannotated tweet sentiment dataset - https://www.aclweb.org/anthology/N18-1171/ from [Sentiment Analysis: It’s Complicated!](https://www.aclweb.org/anthology/N18-1171/) - https://github.com/networkdynamics/mcgill-tsa
* Freebase Annotations for TRAC KBA challenge (includes twitter stream data) - http://aws-publicdatasets.s3.amazonaws.com/trec/kba/FAKBA1/index.html
* Twitter Machine Translation corpus - http://komunitatea.elhuyar.eus/tweetmt/resources/
* Twitter Language Identification - http://komunitatea.elhuyar.eus/tweetlid/
* Twitter classification using open directory project categories - http://www.zubiaga.org/datasets/odptweets/
* Twitter Trending Topic - http://nlp.uned.es/~damiano/datasets/TT-classification.html
* Various Twitter datasets for personality classification as well as MSM2013 entity linking data - https://web.sas.upenn.edu/danielpr/resources/
* Weibo and Twitter data with 5,000 claims that scale to five million relevant microblog posts available at: http://alt.qcri.org/~wgao/data/rumdect.zip [Paper](https://www.ijcai.org/Proceedings/16/Papers/537.pdf)
* Open domain targeted sentiment - https://web.archive.org/web/20200427155239/http://www.m-mitchell.com/code/
* Tweet span sentiment identification - http://alt.qcri.org/semeval2014/task9/index.php?id=data-and-tools
* Twitter Stereotype Extraction - https://github.com/kennyjoseph/twitter_stereotype_extraction
* [Twitter Identity Extraction](https://github.com/kennyjoseph/identity_extraction_pub/tree/master/python/processed_data)
* Political Parody (politican tweets and their parody tweets) - https://archive.org/details/parody_data_acl20
* Italian Twitter Corpus of Hate Speech - https://github.com/msang/hate-speech-corpus
* TRAC 2020 Multilingual Annotated Corpus of Misogyny and Aggression - https://sites.google.com/view/trac2/shared-task?authuser=0 - [drive](https://drive.google.com/open?id=1MRRWK1t6gO-VoS0TevNK5fFl_dtZHJ_A)
* Detecting Nastiness in Social Media - http://ritual.uh.edu/wp-content/uploads/2017/08/ask.fm_dataset.zip
* Social Bias Frames (Twitter, Reddit, etc for multiple tags) - https://homes.cs.washington.edu/~msap/social-bias-frames/
* User level abusive, hate, and bully classification - https://zenodo.org/record/1184178#.Xgu24UdKh3g
* EveTAR test collection, Arabic Test Collection for multiple information retrieval tasks in Twitter (Event detection, Ad-hoc search, Timeline generation, Real-time summarization) - http://qufaculty.qu.edu.qa/telsayed/evetar/ . It supports:
* MeToo Dataset annotated for Text_Only_Informative,Image_Only_Informative,Directed_Hate,Generalized_Hate,Sarcasm,Allegation,Justification,Refutation,Support,Oppose - https://github.com/akash418/MeTooMMD	
* Arabic HateSpeech annotated corpora - https://github.com/nuhaalbadi/Arabic_hatespeech	
* Arabic Twitter Bots annotated user data - https://github.com/nuhaalbadi/ArabicBots	
* Social Media Mining for Health Applications (Classification, Tagging, and Linking) - https://healthlanguageprocessing.org/smm4h/challenge/ [CodaLab](https://competitions.codalab.org/competitions/20798)	
* Sentiment and Entity Corpus on Climate Change tweets - https://gate.ac.uk/projects/decarbonet/datasets.html	
* Twitter Dialogue Corpus - https://github.com/Phylliida/Dialogue-Datasets
* HAHA - Humor Analysis based on Human Annotation, a task to classify tweets in Spanish as humorous or not, and to determine how funny they are - https://www.fing.edu.uy/inco/grupos/pln/haha/index.html#data
* Multiple Hate speech datasets - https://github.com/leondz/hatespeechdata
* SSIX BREXIT Twitter Annotated Data Set (sentiment) - https://zenodo.org/record/1229649#.XyNZU_hKidY https://bitbucket.org/ssix-project/brexit-gold-standard/src/master/
* HaterNet a system for detecting and analyzing hate speech in Twitter (Spanish) - https://zenodo.org/record/2592149#.XyNbTPhKidY
* Webis Clickbait Corpus 2016 (Webis-Clickbait-16) (2992 tweets) - https://zenodo.org/record/3251557#.XyNcgvhKidY
* Webis Clickbait Corpus 2017 (Webis-Clickbait-17) (38,517 tweets) - https://zenodo.org/record/3346491#.XyNd3_hKidY - [Clickbait Challenge](https://www.clickbait-challenge.org/)
* RepLab Summarization Dataset (also topic labeling) - https://zenodo.org/record/2536801#.XyNdcvhKidY
* FIRE 2018 IRMiDis track dataset: Fact-checkable tweets posted during disasters - https://zenodo.org/record/3336477#.XyNiIPhKidY
* Political leaning of Twitter Users based on list membership (includes 3 months tweets) - https://github.com/klout/opendata/blob/master/political_leaning/README.md
* The UMass Global English on Twitter Dataset - https://www.kaggle.com/rtatman/the-umass-global-english-on-twitter-dataset (This dataset contains tweets from a variety of languages, tagged for whether they are in English or not, whether they contain code-switching, whether they includes names from a different language and whether they were generated automatically.)
* Twitter Sentence Specificity - https://github.com/wjko2/Domain-Agnostic-Sentence-Specificity-Prediction/tree/master/dataset/data
* Sarcasm Detection (Shared Task 2nd FigLang Workshop at ACL 2020) - https://github.com/EducationalTestingService/sarcasm
* Webis Clickbait Corpus 2017 - https://webis.de/data/webis-clickbait-17
* Tweet Wikipedia Entity Prediction - https://github.com/lunafeng/ELTDS
* Twitter data annotated with topic labels - http://www.site.uottawa.ca/~diana/resources/
* Twitter data with annotated location expressions at city, state/province, and country level - http://www.site.uottawa.ca/~diana/resources/
* Language specificity in Tweets - https://github.com/cs329yangzhong/specificityTwitter
* Geolocation prediction from text - https://archive.org/details/twitter_cikm_2010
* Social Bias Inference Corpus (SBIC) contains 150k structured annotations of social media posts - https://homes.cs.washington.edu/~msap/social-bias-frames/
* Civil Unrest Tweets - https://github.com/AADeLucia/JHU-CUT
* Japanese Tweet Sentiment Corpus (500k) - http://www.db.info.gifu-u.ac.jp/data/Data_5d832973308d57446583ed9f
* Japanese Covid 19 Tweet Relevance - http://www.db.info.gifu-u.ac.jp/data/Data_5f02db873363f976fce930d1
* Arabic Tweet Sentiment - https://archive.ics.uci.edu/ml/datasets/Twitter+Data+set+for+Arabic+Sentiment+Analysis
* English Spanish Tweet Hate Speech - https://competitions.codalab.org/competitions/19935
* TREC-IS - Detailed annotated Crisis Tweets - http://dcs.gla.ac.uk/~richardm/TREC_IS/2020/data.html
* Hinglish Spanglish Code-Mixed Tweet Sentiment - https://ritual-uh.github.io/sentimix2020/res
* Manually annotated Arabic Sentiment data - https://github.com/motazsaad/arabic-sentiment-analysis
* Semeval 2017 English Arabic Sentiment data - https://alt.qcri.org/semeval2017/task4/index.php?id=results
* Italian tweets factual annotation - https://github.com/evalita2016/data
* Tweet Image to Emoji dataset (4M) - https://www.cs.utexas.edu/~ziad/emoji_visual_sentiment.html
* Visual Public Emotions dataset - https://github.com/cvlab-stonybrook/Emotion-Prediction/tree/master/main/PublicEmotionDatasets
* EmotionGIF 2020 Shared task on tweet text to GIF category prediction - https://sites.google.com/view/emotiongif-2020/shared-task/dataset?authuser=0
* iSarcasm - sarcasm, irony, satire, understatement, overstatement, rhetorical question - https://github.com/silviu-oprea/iSarcasm
* Irony Sarcasm Analysis Corpus (includes geolocation info) - http://romanklinger.de/ironysarcasm/
* Tweet text classification benchmark - https://github.com/cardiffnlp/tweeteval
* Unified Multilingual Sentiment Analysis Benchmark - https://github.com/cardiffnlp/xlm-t
* Feel-IT - Italian Tweet Sentiment and Emotion - https://towardsdatascience.com/sentiment-analysis-and-emotion-recognition-in-italian-using-bert-92f5c8fe8a2
* Multilingual Twitter Hatespeech with Demographic Attributes - https://github.com/xiaoleihuang/Multilingual_Fairness_LREC
* Gender and Individual/Org predictor from Tweet User - https://bitbucket.org/mdredze/demographer
* Hurricane Emotions - https://github.com/shreydesai/hurricane
* COVID19 Fake News Detection in English - https://competitions.codalab.org/competitions/26655 - https://constraint-shared-task-2021.github.io/ 
* Hostile Post Detection in Hindi - https://competitions.codalab.org/competitions/26654 - https://constraint-shared-task-2021.github.io/
* Implicit and Explicit Hate - https://github.com/GT-SALT/implicit-hate
* SMILE: Twitter Emotion Classification using Domain Adaptation - https://www.kaggle.com/ashkhagan/smile-twitter-emotion-dataset
* Sarcasm Detection based on User and Reader - https://github.com/bshmueli/SPIRS
* Arabic Tweet Sentiment - https://github.com/komari6/Arabic-twitter-corpus-AJGT [Parsed format on Huggingface Dataset](https://huggingface.co/datasets/ajgt_twitter_ar)
* Tweets Hate Speech Detection - https://huggingface.co/datasets/tweets_hate_speech_detection
* TRACT: Tweets Reporting Abuse Classification Task Corpus - https://data.mendeley.com/datasets/my2vkfyffd/2
* TM-Senti: large-scale, multilingual and longitudinal Twitter sentiment dataset sampled through distant supervision from the Twitter Stream Grab archive (2013 - 2020, 7 langs) - https://figshare.com/articles/dataset/TM-Senti/16438281
* DynaSent: Dynamic Sentiment Analysis Dataset - https://github.com/cgpotts/dynasent
* ICON2021 Shared Task on Multilingual Gender Biased and Communal Language Identification - https://competitions.codalab.org/competitions/35482
* COMRADES Crowdsourced Informativeness Dataset (CCSID) - https://figshare.com/articles/dataset/COMRADES_Crowdsourced_Informativeness_Datased_CCSID_/5787693
* Hate Speech Dataset - https://github.com/Mainack/hatespeech-data-HT-2017
* Estimating Ideological Positions with Twitter Data - https://github.com/pablobarbera/twitter_ideology
* SemEval-2018 task 3 - Irony detection in English tweets - https://competitions.codalab.org/competitions/17468 - Data Download - https://github.com/Cyvhee/SemEval2018-Task3
* SemEval-2018 Task 1: Affect in Tweets (AIT-2018) - https://competitions.codalab.org/competitions/17751 - Data Download - http://saifmohammad.com/WebDocs/AIT-2018/AIT2018-DATA/SemEval2018-Task1-all-data.zip
* SemEval 2022 - Task 6 (iSarcasmEval) : Intended Sarcasm Detection In English and Arabic - https://github.com/iabufarha/iSarcasmEval
* Annotating Offensive Language Datasets with Annotators’ Disagreement - https://github.com/dhfbk/annotators-agreement-dataset
* Large Scale Crowdsourcing and Characterization of Twitter Abusive Behavior - https://zenodo.org/record/3706866
* Learning With Disagreements (Le-Wi-Di), 2nd edition - https://codalab.lisn.upsaclay.fr/competitions/6146
* EmoThreat: Emotions & Threat Detection in Urdu - https://codalab.lisn.upsaclay.fr/competitions/5718 - https://sites.google.com/view/multi-label-emotionsfire-task/home
* TempoWiC - Detecting Meaning Shift in Social Media - https://codalab.lisn.upsaclay.fr/competitions/5360
* UMSAB, the Unified Multilingual Sentiment Analysis Benchmark - https://github.com/cardiffnlp/xlm-t#3---umsab-the-unified-multilingual-sentiment-analysis-benchmark
* Shared Task on Threat, Aggression and Cyberbullying Identification (TRAC - 2022) - https://codalab.lisn.upsaclay.fr/competitions/4753#learn_the_details-overview
* TRAC 2022 Shared Task on Bias, Threat and Aggression Identification in Context (BiTAg-Con) - https://codalab.lisn.upsaclay.fr/competitions/5792
* SMM4H 2022 - Task 1 - ADE Mining in English Tweets - https://codalab.lisn.upsaclay.fr/competitions/2073
* SMM4H 2022 - Task 9 Classification of social media forum posts self-reporting exact age - https://codalab.lisn.upsaclay.fr/competitions/3646
* Fine-Grained Hate Speech Detection on Arabic Twitter - https://codalab.lisn.upsaclay.fr/competitions/2324 https://codalab.lisn.upsaclay.fr/competitions/2332 https://codalab.lisn.upsaclay.fr/competitions/2334
* NaijaSenti: A Nigerian Twitter Sentiment Corpus for Multilingual Sentiment Analysis - https://zenodo.org/record/6538055
* CHIME dataset: Identifying and Categorizing Disaster-Related Tweets	- https://github.com/Project-EPIC/chime-annotation
* A Survey and Experiments on Annotated Corpora for Emotion Classification in Text - https://github.com/sarnthil/unify-emotion-datasets/tree/master/datasets
* Stance Sentiment Emotion Corpus (SSEC): An annotation of the SemEval 2016 Twitter stance and sentiment corpus with emotion labels - https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/stanceemotion/
* Hate Speech / Offensive Speech in the US 2020 Elections: Corpus for hate speech detection and stance detection - https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/stance-hof/
* Visual Emotion Corpus: Visual Emotion Corpus - https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/visual-emotion-corpus/
* DISARM: Detecting the Victims Targeted by Harmful Memes - https://github.com/Shiv681991/DISARM
* Multimodal-Sarcasm-Explanation--MuSE - https://github.com/LCS2-IIITD/Multimodal-Sarcasm-Explanation-MuSE
* Multilingual code-mixed datasets for classification - https://github.com/LCS2-IIITD/Code-mixed-classification/tree/main/data [Same version](https://github.com/LCS2-IIITD/HIT-ACL2021-Codemixed-Representation/tree/main/data)
* Hinglish code-mixed hate detection - https://github.com/LCS2-IIITD/Hinglish_offense_detection-Neurocomputing2021
* Hindi Ho​st​ile Posts in ​Regional L​anguages dur​ing Emerge​ncy Si​tuation - https://competitions.codalab.org/competitions/26654#learn_the_details-dataset
* HSpam14 Dataset (14M tweets tagged for spam or not using various techniques) - https://personal.ntu.edu.sg/axsun/datasets.html
* Automatic Misogyny Identification (AMI) - https://amievalita2020.github.io/data/
* 2nd Hate Speech Detection Task at Evalita 2020 - https://github.com/msang/haspeede
* IronITA (Irony Detection in Italian Tweets) - http://www.di.unito.it/~tutreeb/ironita-evalita18
* Offensive language dataset of Croatian, English and Slovenian comments FRENK 1.1 - https://www.clarin.si/repository/xmlui/handle/11356/1462
* Extraction of Informative COVID-19 Danish Tweets - https://github.com/beaol/Finding-the-needle-in-a-haystack-Extraction-of-Informative-COVID-19-Danish-Tweets



### Stance detection
* Stance in Replies and Quotes (SRQ): A New Dataset For Learning Stance in Twitter Conversations - https://zenodo.org/record/3609277#.XyNbovhKidY
* Roumors dataset - https://github.com/vahedq/rumors/tree/master/data
* Twitter Stance re-annotated with emotion - http://www.romanklinger.de/ssec/
* Twitter Titling Corpus (stance towards presidents) - https://heidata.uni-heidelberg.de/dataset.xhtml?persistentId=doi:10.11588/data/IOHXDF
* Stance and Gender Detection in Tweets on Catalan Independence@Ibereval 2017 - https://stel.ub.edu/Stance-IberEval2017/
* Danish political stance dataset - https://figshare.com/articles/dataset/Danish_political_stance_dataset/12382592
* Twitter data annotated with stance toward multipe targets - http://www.site.uottawa.ca/~diana/resources/
* SemEval 2016 Task 6: Detecting Stance in Tweets - http://alt.qcri.org/semeval2016/task6/
* Tweet stance detection - https://github.com/kennyjoseph/constance
* SardiStance at EVALITA 2020 - https://github.com/mirkolai/evalita-sardistance


### Tagging

* Xlime - multi layered annotations in german, spanish and Italian - Sentiment, POS, NER - https://github.com/lrei/xlime_twitter_corpus - https://www.clarin.si/repository/xmlui/handle/11356/1078
* UD_Italian-PoSTWITA: Italian Tweet Universal Dependencies - https://github.com/UniversalDependencies/UD_Italian-PoSTWITA [Another version with more details](https://github.com/conllul/UL_Italian-PoSTWITA)
* Ark POS tagging using user embedding as features - https://github.com/bmurali1994/socialnets_postagging
* Ark POS tagged data with original tweet JSON - https://github.com/brendano/ark-tweet-nlp/tree/master/data/twpos-data-v0.3-original-tweets
* Multiple twitter datasets from IIIT Delhi (includes details on Indian political candidates, code switched POS and NER) - http://precog.iiitd.edu.in/resources.html
* Italian Tweet Named Entity Linking - https://github.com/swapUniba/neel-it-twitter
* Italian Twitter datasets for NER, POS, Supersense tagging: http://www.evalita.it/ 
* NEEL Microposts challenge - http://microposts2016.seas.upenn.edu/
* Yodie corpora: https://gate.ac.uk/applications/yodie.html
* English web text - https://github.com/UniversalDependencies/UD_English-EWT
* Twitter treebank - https://github.com/Oneplus/Tweebank
* Twitter UD dependency parsing for african american dialect as well as normal english - http://slanglab.cs.umass.edu/TwitterAAE/
* Linguistic Code-Switching Evaluation Benchmark - https://ritual.uh.edu/lince/
* Aspect Term-Polarity Co-Extraction - https://github.com/ArrowLuo/DOER
* Tweets mentinioning drugs and medication (tagging task) - https://healthlanguageprocessing.org/pubs/journals/kusuri/
* Drug entity linking on Tweets - https://healthlanguageprocessing.org/sharedtask2/smm4h-sharedtask-2017/ (additional tweet datasets - https://healthlanguageprocessing.org/software-and-downloads/)
* Tweet, FB, and WhatsApp Code-Switched POS tagging - http://amitavadas.com/Code-Mixing.html
* Lowlands Cost-sensitive POS tagging data - https://bitbucket.org/lowlands/costsensitive-data/src/master/
* Entity Profiling in Microblog Posts (Aspect phrases and Opinion Targets) - http://nlp.uned.es/~damiano/datasets/entityProfiling_ORM_Twitter.html
* Twitter Domain Adapted POS dataset - https://github.com/guitaowufeng/TPANN/tree/master/data
* Clickbait spotting and spoling - https://webis.de/data/webis-clickbait-22.html https://webis.de/data/webis-clickbait-17.html https://webis.de/data/webis-clickbait-16.html
* POS, NER, Semantic Role for disaster events - https://github.com/Project-EPIC/epic-annotation
* BioClaim: Biomedical claims in tweets, BEAR: Biomedical Entities and Relations in Tweets, CoVERT: Fact-checking labels and evidence for tweets about Covid-19 - https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/bioclaim/
* Serbian Twitter training corpus ReLDI-NormTagNER-sr 2.1 - https://www.clarin.si/repository/xmlui/handle/11356/1240

#### NER datasets

* WNUT 2016: Twitter NER - https://github.com/aritter/twitter_nlp/tree/master/data/annotated/wnut16
* WNUT 2017: Emerging Entities dataset - https://github.com/leondz/emerging_entities_17 [Guidelines](https://github.com/gaguilar/NER-WNUT17/tree/master/data)
* Italian - http://neel-it.github.io/
* German, Italian, Spanish - https://github.com/lrei/xlime_twitter_corpus
* Hindi English code-mixed - https://github.com/SilentFlame/Named-Entity-Recognition
* Densely annotated Wikipedia - https://github.com/klout/opendata/tree/master/wiki_annotation
* Spanish English and Arabic Egyptian - https://code-switching.github.io/2018/#shared-task-id
* SocialDisNER corpus: gold standard annotations for detection of disease mentions in Spanish tweets - https://zenodo.org/record/6773099
* ProfNER corpus: gold standard annotations for profession detection in Spanish COVID-19 tweets - https://zenodo.org/record/4563995
* Many code-switched - http://emnlp2014.org/workshops/CodeSwitch/call.html
* Croatian - https://www.clarin.si/repository/xmlui/handle/11356/1241
* Serbian - https://www.clarin.si/repository/xmlui/handle/11356/1240
* Turkish - https://github.com/dkucuk/Tweet-Dataset-NER-SD
* Named Entity Recognition on Turkish Tweets: http://optima.jrc.it/Resources/2014_JRC_Twitter_TR_NER-dataset.zip
* French - http://cap2017.imag.fr/competition.html
* Slovenian - https://www.clarin.si/repository/xmlui/handle/11356/1123
* Telugu - https://github.com/anikethjr/NER_Telugu
* German Italian and Spanish - https://github.com/lrei/xlime_twitter_corpus
* Hindi - http://au-kbc.org/nlp/ESM-FIRE2015/
* Temporally-Informed Analysis of Named Entity Recognition - https://zenodo.org/record/3899040#.XyNTV_hKidY - https://github.com/shrutirij/temporal-twitter-corpus
* Code Switched NER - https://code-switching.github.io/2018/#shared-task-id
* Bullying Traces Data Set - https://research.cs.wisc.edu/bullying/data.html
* Hindi English Codemixed NER - https://github.com/SilentFlame/Named-Entity-Recognition
* Cyberthreat detection - https://github.com/ndionysus/multitask-cyberthreat-detection - https://github.com/ndionysus/twitter-cyberthreat-detection
* Lowlands LREC 2014 corrected + new benchmarks - https://bitbucket.org/lowlands/release/src/master/LREC2014/twitter_ner/
* ParsTwiNER: Parsi Twitter NER - https://github.com/overfit-ir/parstwiner
* MultiModal NER - https://github.com/RiTUAL-UH/multimodal_NER
* DFKI MobIE Corpus (formerly "DAYSTREAM Corpus") - 3,232 German-language documents for NER - https://github.com/dfki-nlp/mobie
* TwiCS: Microblog Entity Mention Detection with Multi-pass Lightweight Computations - https://github.com/dalakada/TwiCSv2/tree/master/data
* Tweebank NER - https://github.com/social-machines/TweebankNLP
* Information Extractor for Conversational Systems in Indian Languages (IECSIL, NER + REL, Hindi, Tamil, Malayalam, Telugu and Kannada)- https://github.com/BarathiGanesh-HB/ARNEKT-IECSIL [Password=arnekt@iecsil2018](https://github.com/BarathiGanesh-HB/ARNEKT-IECSIL/issues/2#event-6105560970)
* Hashtag Segmentation Dataset - https://github.com/prashantkodali/HashSet
* Sentiment Scopes for Entity-Level Sentiment Analysis [en, es] - https://github.com/leodotnet/sentimentscope
* MobIE: A German Dataset for Named Entity Recognition, Entity Linking and Relation Extraction in the Mobility Domain - https://github.com/dfki-nlp/mobie
* DFKI Product Corpus - 174 English web pages and social media posts annotated for product and company named entities, and the relation CompanyProvidesProduct: https://github.com/DFKI-NLP/product-corpus
* DFKI SmartData Corpus, a dataset of 2598 German-language documents which has been annotated with fine-grained geo-entities, such as streets, stops and routes, as well as standard named entity types - https://github.com/DFKI-NLP/smartdata-corpus
* SMM4H'2022, Task 10 - Detection of disease mentions in tweets–SocialDisNER - https://codalab.lisn.upsaclay.fr/competitions/3531
* METS-CoV: A Dataset of Medical Entity and Targeted Sentiment on COVID-19 Related Tweets - https://github.com/YLab-Open/METS-CoV
* TweetBank-NER - https://github.com/mit-ccc/TweebankNLP

### Entity Linking	
* 282 langauge entity linking data based on Wikipedia - http://nlp.cs.rpi.edu/wikiann/	
* NEEL Microposts challenge - http://microposts2016.seas.upenn.edu/
* Yodie corpora: https://gate.ac.uk/applications/yodie.html	
* https://github.com/juand-r/entity-recognition-datasets
* Sense disambiguation/Entity Linking - https://github.com/lunafeng/ELTDS
* Twitter At the Grammy's - Entity Linking and Clustering - https://bitbucket.org/mdredze/tgx
* Entity Clustering - https://bitbucket.org/noandrews/phyloinf
* NEEL v2 + IE + IR data from Microsoft - https://www.microsoft.com/en-us/download/details.aspx?id=52530
* Twitter NEED - https://github.com/badiehm/TwitterNEED
* WSDM 2012 - https://github.com/dice-group/gerbil/issues/46#issuecomment-257821253 - https://edgar.meij.pro/dataset-adding-semantics-microblog-posts/?utm_source=bit.ly&utm_medium=linked&utm_campaign=myblog
* Multimodal Entity Linking in Tweets - https://github.com/OA256864/MEL_Tweets
* MobIE: A German Dataset for Named Entity Recognition, Entity Linking and Relation Extraction in the Mobility Domain - https://github.com/dfki-nlp/mobie
* Twitter Multimodal Entity Linking using user mentions - https://github.com/seukgcode/MEL-GHMFC/tree/main/datasets/Twitter-MEL
* Italian tweets Named Entity Linking - https://github.com/evalita2016/data
* Entity Linking in Tweets for Book and Movie domain - https://github.com/sujanucsc/IEL-Twitter
* Implicit-Entity-Linking-in-Tweets-Resources-and-Dataset (fine-grained NER and implicit and explicit entities, 7.5K tweets) - https://github.com/HawreH/Implicit-Entity-Recognition-and-Linking-in-Tweets-Resources-and-Dataset/tree/master/Dataset
* Implicit Entity Linking in Tweets (600 tweets) - https://github.com/sujanucsc/IEL-Twitter


### Relation Extraction
* REDIT - A relation extraction module for Tint - https://github.com/dhfbk/redit

### Machine Translation
* TwitterMT - http://komunitatea.elhuyar.eus/tweetmt/resources/#Downloads
* Parallel text extracted from twitter and Weibo - http://www.cs.cmu.edu/~lingwang/microtopia/#twitter

### Paraphrase identification
* Paraphrase identification - https://github.com/cocoxu/SemEval-PIT2015
* URL base large scale paraphrase dataset - https://github.com/lanwuwei/Twitter-URL-Corpus
* Twitter Paraphrase Corpus - https://github.com/jpcorb20/bet-backtranslation-paraphrase-experiment/tree/master/datasets


### Rumour detection 

* Twitter 15 and Twitter 16 rumour detection in tweet trees - https://github.com/majingCUHK/Rumor_RvNN
* PHEME rumour detection data - https://figshare.com/articles/PHEME_dataset_of_rumours_and_non-rumours/4010619
* RumDetect combined with PHEME - https://github.com/majingCUHK/Rumor_GAN - combined data - https://www.dropbox.com/s/46r50ctrfa0ur1o/rumdect.zip?dl=0
* RumorEval 2019 data - https://figshare.com/articles/RumourEval_2019_data/8845580
* Augmented dataset of rumours and non-rumours for rumour detection - https://zenodo.org/record/3269768#.XyNe3fhKidY
* Tweet Check-Worthiness - https://sites.google.com/view/clef2020-checkthat/tasks/tasks-1-5-check-worthiness?authuser=0
* Profiling fake news spreaders on Twitter - https://pan.webis.de/clef20/pan20-web/author-profiling.html
* Twitter Claim Detection from Online Content - https://github.com/LCS2-IIITD/LESA-EACL-2021
* Twitter Death Hoaxes dataset - https://figshare.com/articles/dataset/Twitter_Death_Hoaxes_dataset/5688811

### Fact Checking
* On the Role of Images for Analyzing Claims in Social Media - https://zenodo.org/record/4592249
* Covid 19 claim detection - https://github.com/LCS2-IIITD/LESA-EACL-2021


### Treebank and parsing	
* English web text - https://github.com/UniversalDependencies/UD_English-EWT	
* Twitter treebank - https://github.com/Oneplus/Tweebank	
* Twitter UD dependency parsing for african american dialect as well as normal english - http://slanglab.cs.umass.edu/TwitterAAE/	

### Question answering	
* Tweet QA - https://tweetqa.github.io/


### Conversations

* Twitter Chat Corpus - https://github.com/marsan-ma/chat_corpus
* Microsoft Research Social Media Conversation Corpus - https://www.microsoft.com/en-us/download/details.aspx?id=52375
* Coreference Resolution in Twitter Conversations - https://github.com/verosol/e2e-coref-to-Twitter


### Information Retrieval

* Signal-1M - https://research.signal-ai.com/datasets/signal1m-tweetir.html [tweets data](https://github.com/igorbrigadir/newsir16-data/tree/master/twitter/curated) - Related to https://research.signal-ai.com/newsir16/signal-dataset.html

### Multimodal

* Hate speech images - https://github.com/imatge-upc/hate-speech-detection
* Hate Speech Detection in Multimodal Publications - https://gombru.github.io/2019/10/09/MMHS/
* Text-Image Relationship in Twitter - https://github.com/danielpreotiuc/text-image-relationship
* Reaction GIF - Tweet and their GIF Reactions labeled with sarcarsm - https://github.com/bshmueli/ReactionGIF
* Target-Oriented Multimodal Sentiment Classification - https://github.com/jefferyYu/TomBERT/tree/master/absa_data

### Sentence Similarity

* Twitter4SSE (Co-QuoteTweet, Co-Reply) - https://github.com/marco-digio/Twitter4SSE

### Summarization

* Summarizing Tweets - https://github.com/cocoxu/twittersummarization
* Disaster Tweet Summarization - https://github.com/krudra/disaster_summarizer_TWEB_2018
* RepLab 2013 (Entity-Oriented Summaries for Reputation Management) - http://nlp.uned.es/replab2013/ https://zenodo.org/record/2536801#.XVrin-hKh3g
* ISSumSet: A Tweet Summarization Dataset Hidden in a TREC Track - https://github.com/AlexisDusart/ISSumSet
* Capitalizing on a TREC Track to Build a Tweet Summarization Dataset - https://github.com/AlexisDusart/SetSummTweet
* TES 2012-2016 tweet summary using Wikipedia Current Event portal - https://github.com/AlexisDusart/TSSuBERT/tree/main/TES%202012-2016
* Twitter event datasets (2012-2016, 30 events) - https://figshare.com/articles/dataset/Twitter_event_datasets_2012-2016_/5100460

### Bot Detection
* [TwiBot-22: Towards Graph-Based Twitter Bot Detection](https://twibot22.github.io/)- https://github.com/LuoUndergradXJTU/TwiBot-22

### RecSys
* Cross-Domain Rating Datasets from Structured Data on Twitter - https://github.com/sidooms/Twitter-ratings
* A Movie Rating Dataset Collected From Twitter - https://github.com/sidooms/MovieTweetings
* Twitter RecSys Challenge 2020 - http://www.recsyschallenge.com/2020/
* Twitter RecSys Challenge 2021 - https://www.recsyschallenge.com/2021/


### General

* SocialLink is a publicly-available Linked Open Data dataset that matches social media accounts on Twitter to the corresponding entities in multiple language chapters of DBpedia - https://springernature.figshare.com/articles/dataset/ - [Github](https://github.com/Remper/sociallink)SocialLink_knowledge_transfer_between_social_media_and_linked_open_data/5235823/1
* Tweets informing about resource needs and availabilities in post-disaster situation - https://zenodo.org/record/2649794#.X7vpaGhKh3g
* Paraphrase identification - https://github.com/cocoxu/SemEval-PIT2015
* URL base large scale paraphrase dataset - https://github.com/lanwuwei/Twitter-URL-Corpus
* Language identification code-switched - http://www.care4lang.seas.gwu.edu/cs2/call.html
* Linked Open Data dataset that matches social media accounts on Twitter to the corresponding entities in multiple language chapters of DBpedia  - https://zenodo.org/record/1451797#.XyNYM_hKidY
* Tweets in Space: Geo-tagged Tweet IDs 08/03/18 - 01/12/20 - https://zenodo.org/record/3608252#.XyNacfhKidY
* Fake Health News detection, which includes news contents, news reviews, social engagements and user network - https://zenodo.org/record/3862989#.XyNas_hKidY
* Tweets with reverse geo-tagging - https://zenodo.org/record/11661#.XyNfv_hKidY
* ULSN: A dataset for User Profile Linkage (From Twitter to Quora) - https://zenodo.org/record/3837711#.XyNgd_hKidY
* Multiple corpus for Twitter LangId, NER, etc - https://github.com/dimazest/2018-langid/tree/master/supplement
* Celebrity Profiling - Celebrity Tweet Profiles liked with demographic attributes and Wikidata - https://github.com/webis-de/ACL-19/tree/master/celebrity-profiling
* Topical Attention Election and Brexit - https://github.com/somethingx01/TopicalAttentionElection https://github.com/somethingx01/TopicalAttentionBrexit
* Hashtag segmentation - https://github.com/mounicam/hashtag_master
* English Twitter corpus (Geo-Tweets2019) built for training dialect-sensitive word embeddings - https://yuxingch.github.io/DialectGram/
* Many twitter datasets from ICWSM 2017 - https://zenodo.org/search?page=1&size=20&q=ICWSM
* Arabic English parallel Tweets - https://alt.qcri.org/resources/bilingual_corpus_of_parallel_tweets
* Voter Fraud Tweet dataset - https://voterfraud2020.io/
* Multiple Arabic Tweet datasets - http://qufaculty.qu.edu.qa/telsayed/datasets/
* Sentiment Analysis for Indian Languages (HI, BN, TM tweets) - http://amitavadas.com/SAIL/data.html (Download from: http://amitavadas.com/SAIL/Data/)
* Twitter customer care conversations dataset - https://github.com/IBM/twitter-customer-care-document-prediction
* WebLogo - 2m logo images from Twitter belonging to o specific logo types - https://weblogo2m.github.io/
* Disaster Tweet Corpus - https://zenodo.org/record/3713920
* Realtime classification of Twitter Trends - http://nlp.uned.es/~damiano/datasets/TT-classification.html
* RepLab 2014 (tweeet topic and tweet author reputation) - http://nlp.uned.es/replab2014/#dataset
* RepLab 2013 (entity relevance, polarity, clustering) - http://www.evall.uned.es/evaluate_using_benchmark#benchmark/description
* Papers and codes with Twitter datasets - https://index.quantumstat.com/#twitter
* Hateful user dataset - https://www.kaggle.com/manoelribeiro/hateful-users-on-twitter [Source](https://github.com/hate-alert/Hateful-users-detection)
* Dataset of public interest interventions on Twitter for politicians and candidates during the 2020 US General Election - https://github.com/SMAPPNYU/twitter_elections_public_interest
* A directory of local news outlets by state and medium. Includes social media accounts for local news outlets - https://github.com/yinleon/LocalNewsDataset
* Tweets about the Top Companies from 2015 to 2020 - https://www.kaggle.com/omermetinn/tweets-about-the-top-companies-from-2015-to-2020
* 40k full Twitter user profile data (including who they follow!) - https://www.kaggle.com/hwassner/TwitterFriends
* Twitter User Demographics Prediction - https://www.kaggle.com/crowdflower/twitter-user-gender-classification
* Twitter Social Network [ASU] - https://www.kaggle.com/mathurinache/twitter-edge-nodes [Original Data](http://datasets.syr.edu/datasets/Twitter.html) [Other OSN network data](http://datasets.syr.edu/pages/datasets.html)
* Twitter event datasets (2012-2016, 30 events) - https://figshare.com/articles/dataset/Twitter_event_datasets_2012-2016_/5100460
* SMILE Twitter Emotion - https://figshare.com/articles/dataset/smile_annotations_final_csv/3187909
* Early Risk prediction from social media - https://erisk.irlab.org/
* MediaEval 2020: Various datasets for media evaluation includes Fake News tweet data - https://multimediaeval.github.io/editions/2020/
* Smappdragon is a set of tools for working with twitter data - https://github.com/SMAPPNYU/smappdragon https://github.com/SMAPPNYU/pysmap
* MultiLexNorm: A Shared Task on Multilingual Lexical Normalization - https://bitbucket.org/robvanderg/multilexnorm/src/master/
* Ukraine and Russia Conflict Tweet IDs - https://github.com/echen102/ukraine-russia
* NELA-GT-2021: A Large Multi-Labelled News Dataset for The Study of Misinformation in News Articles (contains tweets embedded in news articles) - https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/RBKVBM
* Information Seeking in Academic Conferences - https://zenodo.org/record/819537
* TimeLMs: Diachronic Language Models Evaluation for Tweets - https://github.com/cardiffnlp/timelms
* EvoNLP Shared Task: Temporal Meaning Shift - https://sites.google.com/view/evonlp/shared-task
* Interactive Tagging Networks (Following/Followers and Tags on 1 million Twitter Users) - https://zenodo.org/record/16267
* User Movement Analysis - https://github.com/Project-EPIC/Twitter-Movement-Derivation/tree/master/All-Coded-Data


### Tools, Tips, and Tricks

* General tricks on using the Twitter search API properly with custom filters - https://github.com/igorbrigadir/twitter-advanced-search
* Important time stamps in history of Twitter - https://github.com/igorbrigadir/twitter-history
* TweetedAt timestampt from tweet ID - https://github.com/oduwsdl/tweetedat
* Twitter API v2 tutorial - https://github.com/twitterdev/getting-started-with-the-twitter-api-v2-for-academic-research
* Twarc - https://github.com/DocNow/twarc/
* Facepager - https://github.com/strohne/Facepager
* Official Twitter Bulk Dataset downloader for Academic Use cases - https://developer.twitter.com/apitools/downloader
* Processing Tweets - https://colab.research.google.com/drive/1Uoog-scrKhLX3QZmrs1ClxCFdGIMH88i?usp=sharing#scrollTo=PmPc5qiIW6Fa
* Ekphrasis is a text processing tool - https://github.com/cbaziotis/ekphrasis
* SocialMediaIE - https://github.com/socialmediaie/SocialMediaIE
* TwitterNER - https://github.com/napsternxg/TwitterNER
* TweetNLP - https://tweetnlp.org/
* StoryWrangler: ngrams trends in Tweets - https://storywrangling.org/about [Code](https://gitlab.com/compstorylab/storywrangler)
* Contagiograms: language specific retweet frequency - https://gitlab.com/compstorylab/contagiograms
* Happy Words from Hedonometer - https://hedonometer.org/words/labMT-en-v2/
* Twitter-Text Official Library for Parsing Tweets - https://github.com/twitter/twitter-text
* Twitter-Stanza - https://github.com/mit-ccc/TweebankNLP

### Embeddings

* Word Embedding Data Sets Learned from 400M Tweets and General Data - https://zenodo.org/record/581402#.XyNhUPhKidY
* Glove Word Embeddings - https://zenodo.org/record/3237458#.YEo-eZ1Kh3g
* Monthly word embeddings for Twitter random sample (English, 2012-2018) - https://zenodo.org/record/3527983
* Twitter Sent2Vec - https://github.com/epfml/sent2vec##downloading-pre-trained-models
* TimeLMs: Diachronic Language Models from Twitter - https://github.com/cardiffnlp/timelms
* Cross-lingual word embeddings from Twitter - https://github.com/pedrada88/crossembeddings-twitter
* Tweet Word Embeddings - https://tweetnlp.org/resources/



### Unlabled topic specific data dumps

* Covid-19 Twitter chatter dataset for scientific use - http://www.panacealab.org/covid19/ https://zenodo.org/record/3960911#.XyNW9vhKidY
* Coronavirus Twitter Data: A collection of COVID-19 tweets with automated annotations - https://zenodo.org/record/3897727#.XyNY__hKidY
* Full trump tweet archive - https://github.com/bpb27/trump_tweet_data_archive
* Many US politicians tweet archive (periodically updated) - https://github.com/bpb27/political_twitter_archive
* TweetsCOV19 is a semantically annotated corpus of Tweets about the COVID-19 pandemic (8.1M) - https://data.gesis.org/tweetscov19/
* TweetsKB is a public RDF corpus of anonymized data for a large collection of annotated tweets (2B, periodically updated). - https://data.gesis.org/tweetskb/
* Twitter historical dataset: March 21, 2006 (first tweet) to July 31, 2009 (3 years, 1.5 billion tweets) - https://zenodo.org/record/3833782#.XyNRIvhKidY
* 307'061 verified Twitter accounts and their tweets from 2018-11-20 to 2018-11-28 - https://zenodo.org/record/2223647#.XyNTCvhKidY
* GeoCoV19: A Dataset of 524 Million of Multilingual COVID-19 Tweets with Location Information - https://zenodo.org/record/3878599

## Facebook

### Classification
* Facebook post valence and arousal - http://www.preotiuc.ro/resources.html
* [FB What (or Who) Is Public? Privacy Settings and Social Media Content Sharing](http://eegilbert.org/papers/) - https://github.com/compsocial/WhatWhoCSCW2017
* FB English Hindi Aggresion Identification - https://sites.google.com/view/trac1/shared-task
* FB News Page and Posts - https://bigquery.cloud.google.com/dataset/jbencina-144002:fb_news and https://github.com/jbencina/facebook-news/
* MultiEmotion-It - Italian Multiemotion corpus - https://github.com/RacheleSprugnoli/Esercitazioni_SA/tree/master/dataset
* Sinhala FB Decade Corpora https://github.com/LIRNEasia/FacebookDecadeCorpora


## Instagram

### Multimodal Tasks
* DankMemes 2020 - https://github.com/gianlucalebani/dankmemes2020


## Youtube:

### Classification

* Sentube sentiment - https://github.com/Abdelghafour01/sentube-sentiment
* Multimodal sentiment from video - https://github.com/soujanyaporia/multimodal-sentiment-analysis
* Tamil Malayalam Code-Mix Sentiment - https://dravidian-codemix.github.io/2020/datasets.html
* MultiEmotion-It - Italian Multiemotion corpus - https://github.com/RacheleSprugnoli/Esercitazioni_SA/tree/master/dataset
* JTubeSpeech: Corpus of speech collected from YouTube - https://github.com/sarulab-speech/jtubespeech
* Sentnob: Bengali Youtube Comments Sentiment Dataset - https://www.kaggle.com/cryptexcode/sentnob-sentiment-analysis-in-noisy-bangla-texts
* English YouTube Hate Speech Corpus - https://www.clarin.si/repository/xmlui/handle/11356/1454
* Italian YouTube Hate Speech Corpus - https://www.clarin.si/repository/xmlui/handle/11356/1450
* Sentiment Analysis and Homophobia detection of YouTube comments - https://codalab.lisn.upsaclay.fr/competitions/5310

### Videos

* ClipShots: large-scale dataset for shot boundary detection collected from Youtube and Weibo covering more than 20 categories - https://github.com/Tangshitao/ClipShots


### General

* Trending YouTube Video Statistics [multi-country] - https://www.kaggle.com/datasnaek/youtube-new

## Reddit

### Classification
* Sarcasm detection - https://github.com/SenticNet/CASCADE
* Self-annotated sarcasm corpora - http://nlp.cs.princeton.edu/SARC/2.0/ [Paper](https://www.aclweb.org/anthology/papers/L/L18/L18-1102/)
* Conversational data - https://github.com/PolyAI-LDN/conversational-datasets
* GoEmotions: A Dataset of Fine-Grained Emotions - https://github.com/google-research/google-research/tree/master/goemotions
* Reddit Wallstreetbets Support and Intent Annotated Dataset 2021 - https://zenodo.org/record/5851847#%23.YeO_vhPML8E
* CL-Aff Shared Task: Get it #OffMyChest affective understanding of conversations - https://github.com/kj2013/claff-offmychest
* Us vs. Them: A Dataset of Populist Attitudes, News Bias and Emotions - https://github.com/LittlePea13/UsVsThem
* CAD: the Contextual Abuse Dataset - https://zenodo.org/record/4881008
* MMEmo Corpus: Multi-Modal Emotion Recognition Corpus of Reddit Posts - https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/mmemo/
* Reddit News Chatter Intensity - https://github.com/LCS2-IIITD/ChatterNet
* DEBAGREEMENT: A comment-reply dataset for (dis)agreement detection in online debates - https://scale.com/open-av-datasets/oxford

### Summarization

* Reddit TIFU: Abstractive Summarization of Reddit Posts (120k) - https://github.com/ctr4si/MMN [HF dataset](https://huggingface.co/datasets/reddit_tifu)

### Sequence Tagging
* PASTRIE - MWE annotations - https://github.com/nert-nlp/pastrie


### Named Entitis

* Entity Linking dataset - https://zenodo.org/record/3970806
* GUMReddit (Entity Linking, NER, etc) - https://github.com/universalDependencies/UD_English-GUMReddit/

### Conversations

* Fast Adapation of Predicted User Responses in Goal-Oriented Dialogue - https://competitions.codalab.org/competitions/20152 [Data Source](https://github.com/microsoft/dstc8-reddit-corpus) [HF data](https://huggingface.co/datasets/roskoN/dstc8-reddit-corpus)
* Reddit Writing Prompts - https://huggingface.co/datasets/rewardsignal/reddit_writing_prompts

### Tools
* Data Tools for Reddit - https://github.com/dewarim/data-tools-for-reddit


## Gab

* The Gab Hate Corpus - https://osf.io/edua3/
* Hateful user dataset - https://zenodo.org/record/5140191#.YQBGhI4zY2w [Source](https://github.com/hate-alert/Hateful-users-detection)
* Abuse Detection, Severity and Target Prediction for Gab Posts - https://github.com/mohit3011/AbuseAnalyzer

### Summarization

* TL;DR corpus - https://zenodo.org/record/1168855#.X1WcDGdKidY

### Amazon	
* Irony and sarcasm in reviews - https://github.com/ef2020/SarcasmAmazonReviewsCorpus/wiki	


### eCommerce website in Italy
* Aspect Term Extraction and Aspect-based Sentiment Analysis Task - http://www.di.uniba.it/~swap/ate_absita/dataset.html


## About.me

* User identities from multiple social networks - https://github.com/WING-NUS/aboutme

## Whatsapp

* ICWSM tutorial on collecting WhatsApp data - https://users.ics.aalto.fi/kiran/whatsapp-tutorial/
* Tools for WhatsApp data collection - https://gvrkiran.github.io/whatsapp-tutorial/
* WhatsApp group data: https://dataverse.mpi-sws.org/dataset.xhtml?persistentId=doi:10.5072/FK2/CS7U5P
* Cyberbullying among Italian students - https://github.com/dhfbk/WhatsApp-Dataset

## Delicious 

* SocialBM0311 is a large-scale social tagging/bookmarking dataset collected from Delicious.com - http://www.zubiaga.org/datasets/socialbm0311/

## Ask.fm

* Ask.fm Cyberbullying Corpus - https://ritual.uh.edu/cyberbullying-corpus/


## Flickr

### Popularity prediction
* Social Media Prediction Challenge - http://smp-challenge.com/


## Conversations

* Multiple conversation datasets - https://convokit.cornell.edu/
* Yahoo News Annotated Comments Corpus  - https://github.com/cnap/ynacc
* Multi-Domain Wizard-of-Oz dataset (MultiWOZ), a fully-labeled collection of human-human written conversations spanning over multiple domains and topics - https://github.com/budzianowski/multiwoz

## News Comments

* A Dataset of Journalists' Interactions with Their Readership: When Should Article Authors Reply to Reader Comments?
 - https://github.com/julian-risch/CIKM2020/
* User Engagement in Online Discussions - https://github.com/julian-risch/ICWSM2020
* Top Comment or Flop Comment? Predicting and Explaining User Engagement in Online News Discussions - https://github.com/julian-risch/ICWSM2020
* SFU Opinion and Comments Corpus - https://github.com/sfu-discourse-lab/SOCC
* FRENK-MMC-RTV Slavic news comments moderated by platform - https://www.clarin.si/repository/xmlui/handle/11356/1201 [Paper](https://aclanthology.org/W18-5116/)
* FRENK-STYRIA-24sata 1.0 Croatian news comments moderated by platform - https://www.clarin.si/repository/xmlui/handle/11356/1202 [Paper](https://aclanthology.org/W18-5116/)

## Weibo

* Weibo-Douban user alignment across networks - https://github.com/ChenBaiyang/MAUIL
* Continuously updated Sina Weibo Public Opinion Datasets (only for research) - https://github.com/nghuyong/weibo-public-opinion-datasets
* Tencent Weibo (following network) - https://github.com/dedekinds/Graph-Embedding
* Weibo User Depression Detection Dataset - https://github.com/aidenwang9867/Weibo-User-Depession-Detection-Dataset
* ClipShots: large-scale dataset for shot boundary detection collected from Youtube and Weibo covering more than 20 categories - https://github.com/Tangshitao/ClipShots
* Multimodal entity linking (MEL) - https://github.com/seukgcode/MELBench
* Multilingual EN, JA, ZH Covid Weibo data - https://github.com/sociocom/covid19_dataset
* Social Media Keyphrase Generation - https://github.com/yuewang-cuhk/TAKG
* MELBench - Multimudal Entity Linking - https://github.com/seukgcode/MELBench
* Russia Ukraine Crisis Weibo (RUW) Dataset - https://github.com/yrf1/RussiaUkraine_weibo_dataset


## TikTok 

* MVIndEmo: A Dataset for Micro-video Public Induced Emotion Prediction on Social Media - https://github.com/inspur-hsslab/NeurIPS-Dataset-Induced-Emotion

## Whisper

* Whisper dataset - https://github.com/Mainack/whisper-2014-2016-data-HT-2020
* Hate Speech dataset - https://github.com/Mainack/hatespeech-data-HT-2017


## SMS

* SMS Noun Phrase Detection - https://github.com/statnlp-research/statnlp-datasets/blob/master/dataset/SMSNP_data.zip

## Stormfront

* Hate speech dataset - https://github.com/Vicomtech/hate-speech-dataset

## Meneame

* Dataset of discussion threads from Meneame (Spanish) - https://zenodo.org/record/2536218


## General

* Pheme project: https://www.pheme.eu/software-downloads/
* Many pheme related datasets: https://figshare.com/authors/Arkaitz_Zubiaga/1376367
* Hatespeech term database: https://hatebase.org
* Hatespeech lexicons: http://hatespeech.di.unito.it/resources.html
* https://github.com/sebastianruder/NLP-progress
* 282 langauge entity linking data based on Wikipedia - http://nlp.cs.rpi.edu/wikiann/
* https://github.com/juand-r/entity-recognition-datasets	
* Hashtag generation corpus - https://github.com/yuewang-cuhk/HashtagGeneration
* Klout FB and Twitter user reaction timestamps - https://github.com/klout/opendata/blob/master/when_to_post/README.md
* GSCL Shared Task: Automatic Linguistic Annotation of Computer-Mediated Communication / Social Media (POS and tokenization) https://sites.google.com/site/empirist2015/
* Matching identities across social media platforms - http://lig-membres.imag.fr/gogao/data.html
* Internet Argument Corpus v2 - https://nlds.soe.ucsc.edu/iac2
* Argument Facet Similarity Corpus - https://nlds.soe.ucsc.edu/node/44
* GDELT Social Media In the News - https://blog.gdeltproject.org/daily-updates-to-master-list-of-social-media-in-the-news-in-csv-and-bigquery/ and https://blog.gdeltproject.org/compiling-a-master-list-of-social-media-in-the-news-2016-2019/
* WKWSCI Sentiment Lexicon v1.1 - https://researchdata.ntu.edu.sg/dataset.xhtml?persistentId=doi:10.21979/N9/DWWEBV
* Voat.co dataset - https://zenodo.org/record/5841668
* The MeLa BitChute Dataset - https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/KRD1VS
* Effect of Popularity Shocks on User Behavior - https://zenodo.org/record/5854980#.YjgJAi8RoTs
* SemEval-2022 Shared Task 10: Structured Sentiment Analysis - https://github.com/jerbarnes/semeval22_structured_sentiment
* Dissecting harmful memes for Semantic role labelling of entities - https://codalab.lisn.upsaclay.fr/competitions/906#learn_the_details-evaluation
* Resources for Emotion Analysis: A collection of ressources created at IMS related to emotion and sentiment analysis - https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/emotion/
* MHA-Meme-Leveraging-Sentence-Demarcations-and-Multi-hop-Attention-for-Meme-Affect-Analysis - https://github.com/LCS2-IIITD/MHA-MEME
* Misinfo text datasets - https://github.com/sfu-discourse-lab/MisInfoText
* Wikipedia Talk: A collection of data sets on Wikipedia Talk page discussions - https://figshare.com/projects/Wikipedia_Talk/16731
