# Activity Logs of Group Decision Making in Collaborative Web Search

## Abstract (our paper)
In this paper, we present results of investigation on dynamics of group decision making *how people discuss and make a decision* with collaborative web search.
The primary results showed that (1) at the start and the end of discussion, members engaged in similar behaviors among the groups, (2) discussion time is not significantly related to members' satisfaction with conclusions, and (3) if a member engaged more in behaviors visible among the other members, he/she is likely to be regarded as a leader, who leads group to decision, of the discussion.
We are looking for research collaborators to conduct further analysis.

## Data
All of data is anonymized and it does not include semantic information what they searched or discussed in the experiments.

* `logs/` : Raw activity logs of each group are contained in this directory. The format of each log is in TSV (Tab Separated Values) format `[uid]\t[sec]\t[activity]`.
    * `uid` : User ID in the group.
    * `sec` : Elapsed time (sec.) when the log was recorded. The initial time is zero.
    * `activity` : The type of user's activity; search, view, chat, and bookmark.
* `statistics_log.tsv`: Statistics of activity logs.
* `statistics_post-questionnaire.tsv`: Statistics of the post-questionnaire.
* `README.md` : This file.

## Publication
This dataset was collected for our study. If you make use of this dataset, please cite:

Tatsuya Nakamura, Tomu Tominaga, Miki Watanabe, Nattapong Thammasan, Kenji Urai, Yutaka Nakamura, Kazuhumi Hosoda, Takahiro Hara, and Yoshinori Hijikata, **"Investigation on Dynamics of Group Decision Making with Collaborative Web Search,"** *Proceedings of 2017 IEEE/WIC/ACM International Conference on Web Intelligence (WI)*, August 2017, Leipniz, German, to appear.
