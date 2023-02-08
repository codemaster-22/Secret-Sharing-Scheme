# Secret-Sharing-Scheme

- Secret sharing is a method to divide the secret into many shares/parts such that secret can be constructed by authorized set of shares and unauthorized set of shares reveals least possible amount of information. Secret sharing was first proposed by Shamirs in the paper "How to share a secret?".

- In classical notion if some shares are corrupted then there is no way to identify the errors or recover from those errors, and we also need the schemes to be deterministic because if in case some shareholders lost their shares re-sharing of the shares will be easy. So
ADSS augmented the classic notion with privacy when there is imperfect randomness,authenticity,error correction and also made the scheme deterministic and they call it as Adept secret sharing scheme(ADSS)

- In this report we present our research in the field of secret sharing. We present our work on reducing the time complexity of Error recovery algorithm of adept secret sharing scheme from non polynomial time to polynomial time for threshold schemes with some assumptions on Adversary for restricted set of Access Structures.
