# base5ooo
Tracking Gas Used by Specific Contract
gas = sum(receipt.gasUsed for receipt in receipts if receipt.to == contract)
