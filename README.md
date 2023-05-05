# Notice
Since we cannot log in to the e-mail registered with this github account, We have deprecated this repository and migrated content to a new repository [ppflower/XPOChecker](https://github.com/ppflower/XPOChecker). All subsequent updates will be displayed here..

# XPOChecker Prototype
XPOChecker is designed to detect a certain type of privacy risk, which is called cross-user personal data over-delivery (denoted as XPO).

# Publication

## Cite

[1] Collect Responsibly But Deliver Arbitrarily? A Study on Cross-User Privacy Leakage in Mobile Apps (CCS'2022)

```
@inproceedings{li2022collect,
  title={Collect Responsibly But Deliver Arbitrarily? A Study on Cross-User Privacy Leakage in Mobile Apps},
  author={Li, Shuai and Yang, Zhemin and Hua, Nan and Liu, Peng and Zhang, Xiaohan and Yang, Guangliang and Yang, Min},
  booktitle={Proceedings of the 2022 ACM SIGSAC Conference on Computer and Communications Security},
  pages={1887--1900},
  year={2022}
}
```
## Summary

This paper considers a type of cross-user privacy leakage, more specifically, cross-user personal data over-delivery, denoted as XPO. It means that what a mobile app actually delivers from one user A to another user B is not consistent with what is shown on the app's UI of user B. What actually has been delivered may contain more sensitive information about user A but not shown on UI. And thus, user B can act as an adversary, and capture the underlying (but hidden from UI) sensitive information, such as addresses, emails, and account tokens, from the network traffic. This paper proposes and implements XPOChecker which is able to automatically identify XPO risks. The solution is based on bi-directional thin-slicing to reach the data structure possibly with users' profile information, tries to identify personal data from the data structure, and checks whether data minimization is ensured (i.e., no inconsistency). Several important lessons for app developers are learned from real case studies and a notification campaign has been launched. For more details, please refer to the [paper](https://dl.acm.org/doi/10.1145/3548606.3559371).

# Contact

If you want access to the XPOChecher prototype and the data set, please contact us and tell us your identity and purpose. After we receive the email, we will reply to you as soon as possible with the download link. Our email addresses are as follows:

- Shuai Li (Fudan University) <lis19@fudan.edu.cn>
- Nan Hua (Fudan University) <huan19@fudan.edu.cn>
- Zhemin Yang (Fudan University) <yangzhemin@fudan.edu.cn>

