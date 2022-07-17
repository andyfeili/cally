## Contract Existence Check - Low Level Calls

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-cally.md#h-03-wp-h0-fake-balances-can-be-created-for-not-yet-existing-erc20-tokens-which-allows-attackers-to-set-traps-to-steal-funds-from-future-users

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-04-axelar.md#m-01-low-level-call-returns-true-if-the-address-doesnt-exist

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-06-pooltogether.md#m-05-actual-yield-source-check-on-address-will-succeed-for-non-existent-contract

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-03-lifinance.md#m-11-failed-transfer-with-low-level-call-wont-revert

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-trader-joe.md#m-05-failed-transfer-with-low-level-call-could-be-overlooked

## Set Fee

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-04-backed.md#m-06-might-not-get-desired-min-loan-amount-if-_originationfeerate-changes

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-02-tribe-turbo.md#m-03-slurp-can-be-frontrun-with-fee-increase

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-02-redacted-cartel.md#m-01-manipulations-of-setfee

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-02-concur.md#m-02-unconstrained-fee

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-trader-joe.md#m-01-improper-upper-bound-definition-on-the-fee

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-sandclock.md#m-05-add-a-timelock-to-basestrategysetperffeepct

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-12-nftx.md#m-05-pool-manager-can-frontrun-fees-to-100-and-use-it-to-steal-the-value-from-users

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-12-defiprotocol.md#m-01-missing-cap-on-licensefee

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-overlay.md#m-09-improper-upper-bound-definition-on-the-fee

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-06-tracer.md#m-07-malicious-owner-can-arbitrarily-change-fee-to-any--value

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-05-nftx.md#m-06-manager-can-grief-with-fees

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-cally.md#m-01-owner-can-modify-the-feerate-on-existing-vaults-and-steal-the-strike-value-on-exercise

## Msg.value Validation

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-03-lifinance.md#m-07-erc20-bridging-functions-do-not-revert-on-non-zero-msgvalue

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-cally.md#m-03-users-may-accidentally-overpay-in-buyoption-and-the-excess-will-be-paid-to-the-vault-creator

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-sturdy.md#m-01-possible-lost-msgvalue

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-nested.md#m-03-nestedfactory-ensure-zero-msgvalue-if-transferring-from-user-and-inputtoken-is-not-eth-

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-03-lifinance.md#m-09-should-prevent-users-from-sending-more-native-tokens-in-the-startbridgetokensviacbridge-function

## Special Tokens - Rebasing Tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-cally.md#m-04-vaults-steal-rebasing-tokens-rewards

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-07-connext.md#l-02-deflationary-and-fee-on-transfer-tokens-are-not-correctly-accounted

## Special Tokens - Fee on Transfer Tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-08-realitycards-round-2.md#m-03-deposits-dont-work-with-fee-on-transfer-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-cally.md#m-08-vault-is-not-compatible-with-fee-tokens-and-vaults-with-such-tokens-could-be-exploited

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-04-axelar.md#m-04-unsupported-fee-on-transfer-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-05-88mph.md#m-01-incompatability-with-deflationary--fee-on-transfer-tokens	

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-06-realitycards.md#m-15-deposits-dont-work-with-fee-on-transfer-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-06-tracer.md#m-03-deflationary-tokens-are-not-supported

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-07-pooltogether-micro-1.md#m-03-inconsistent-balance-when-supplying-transfer-on-fee-or-deflationary-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-07-sherlock.md#m-01-incorrect-internal-balance-bookkeeping

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-08-gravitybridge.md#m-04-incorrect-accounting-on-transfer-on-feedeflationary-tokens-in-gravity

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-09-defiprotocol.md#m-02-fee-on-transfer-tokens-can-lead-to-incorrect-approval

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-09-swivel.md#m-04-fee-on-transfer-underlying-can-cause-problems

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-09-yaxis.md#m-01-vaulthelper-deposits-dont-work-with-fee-on-transfer-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-10-defiprotocol.md#m-04-fee-on-transfer-tokens-do-not-work-within-the-protocol

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-10-pooltogether.md#m-01-deposits-dont-work-with-fee-on-transfer-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-10-slingshot.md#m-02-trades-where-totoken-is-feeontransfertoken-might-send-user-less-tokens-than-finalamountmin

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-10-tracer.md#m-02-deposits-dont-work-with-fee-on-transfer-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-malt.md#m-15-bonding-doesnt-work-with-fee-on-transfer-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-malt.md#m-17-auction-collateraltoken-wont-work-if-token-is-fee-on-transfer-token-

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-streaming.md#m-03-this-protocol-doesnt-support-all-fee-on-transfer-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-unlock.md#m-03-support-of-different-erc20-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-vader.md#h-03-vader-contains-a-fee-on-transfer

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-vader.md#m-04-inconsistent-balance-when-supplying-transfer-on-fee-or-deflationary-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-vader.md#m-20-tokens-with-fee-on-transfer-are-not-supported

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-12-pooltogether.md#h-07-contract-does-not-work-with-fee-on-transfer-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-12-sublime.md#m-06-noyieldsol-tokens-with-fee-on-transfer-are-not-supported

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-04-pooltogether.md#m-02-_depositamount-requires-to-be-updated-to-contract-balance-increase

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-behodler.md#m-06-consistently-check-account-balance-before-and-after-transfers-for-fee-on-transfer-discrepencies

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-insure.md#m-05-vaultsol-tokens-with-fee-on-transfer-are-not-supported

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-openleverage.md#m-04-openlevv1closetrade-with-v3-dex-doesnt-correctly-accounts-fee-on-transfer-tokens-for-repayments

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-openleverage.md#m-01-univ2classdexsoluniclasssell-tokens-with-fee-on-transfer-are-not-fully-supported

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-sandclock.md#m-13-incompatibility-with-rebasingdeflationaryinflationary-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-sandclock.md#m-07-vault-cant-receive-deposits-if-underlying-token-charges-fees-on-transfer

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-timeswap.md#m-10-convenience-contract-fails-to-function-if-asset-or-collateral-is-an-erc20-token-with-fees

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-trader-joe.md#m-14-incompatibility-with-rebasingdeflationaryinflationary-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-04-phuture.md#m-07-tokens-with-fee-on-transfer-are-not-supported

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-02-concur.md#m-07-fee-on-transfer-token-donations-in-shelter-break-withdrawals

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-02-tribe-turbo.md#m-04-erc4626-does-not-work-with-fee-on-transfer-tokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-04-backed.md#m-02-protocol-doesnt-handle-fee-on-transfer-tokens 

## ERC721 safeTransfer

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-cally.md#m-09-use-safetransferfrom-instead-of-transferfrom-for-erc721-transfers

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-sandclock.md#m-09-no-use-of-safemint-as-safe-guard-for-users-

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-04-backed.md#m-07-mintborrowticketto-can-be-a-contract-with-no-onerc721received-method-which-may-cause-the-borrowticket-nft-to-be-frozen-and-put-users-funds-at-risk

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-cally.md#m-09-use-safetransferfrom-instead-of-transferfrom-for-erc721-transfers

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-04-backed.md#m-03-sendcollateralto-is-unchecked-in-closeloan-which-can-cause-users-collateral-nft-to-be-frozen

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-06-pooltogether.md#m-07-using-transferfrom-on-erc721-tokens
