 <!-- This file is auto-generated. Please do not modify it yourself. -->
# Protobuf Documentation
<a name="top"></a>

## Table of Contents

- [crypto/vrf/keys.proto](#crypto/vrf/keys.proto)
    - [PrivKey](#crypto.vrf.PrivKey)
    - [PubKey](#crypto.vrf.PubKey)
  
- [zgc/bep3/v1beta1/bep3.proto](#zgc/bep3/v1beta1/bep3.proto)
    - [AssetParam](#zgc.bep3.v1beta1.AssetParam)
    - [AssetSupply](#zgc.bep3.v1beta1.AssetSupply)
    - [AtomicSwap](#zgc.bep3.v1beta1.AtomicSwap)
    - [Params](#zgc.bep3.v1beta1.Params)
    - [SupplyLimit](#zgc.bep3.v1beta1.SupplyLimit)
  
    - [SwapDirection](#zgc.bep3.v1beta1.SwapDirection)
    - [SwapStatus](#zgc.bep3.v1beta1.SwapStatus)
  
- [zgc/bep3/v1beta1/genesis.proto](#zgc/bep3/v1beta1/genesis.proto)
    - [GenesisState](#zgc.bep3.v1beta1.GenesisState)
  
- [zgc/bep3/v1beta1/query.proto](#zgc/bep3/v1beta1/query.proto)
    - [AssetSupplyResponse](#zgc.bep3.v1beta1.AssetSupplyResponse)
    - [AtomicSwapResponse](#zgc.bep3.v1beta1.AtomicSwapResponse)
    - [QueryAssetSuppliesRequest](#zgc.bep3.v1beta1.QueryAssetSuppliesRequest)
    - [QueryAssetSuppliesResponse](#zgc.bep3.v1beta1.QueryAssetSuppliesResponse)
    - [QueryAssetSupplyRequest](#zgc.bep3.v1beta1.QueryAssetSupplyRequest)
    - [QueryAssetSupplyResponse](#zgc.bep3.v1beta1.QueryAssetSupplyResponse)
    - [QueryAtomicSwapRequest](#zgc.bep3.v1beta1.QueryAtomicSwapRequest)
    - [QueryAtomicSwapResponse](#zgc.bep3.v1beta1.QueryAtomicSwapResponse)
    - [QueryAtomicSwapsRequest](#zgc.bep3.v1beta1.QueryAtomicSwapsRequest)
    - [QueryAtomicSwapsResponse](#zgc.bep3.v1beta1.QueryAtomicSwapsResponse)
    - [QueryParamsRequest](#zgc.bep3.v1beta1.QueryParamsRequest)
    - [QueryParamsResponse](#zgc.bep3.v1beta1.QueryParamsResponse)
  
    - [Query](#zgc.bep3.v1beta1.Query)
  
- [zgc/bep3/v1beta1/tx.proto](#zgc/bep3/v1beta1/tx.proto)
    - [MsgClaimAtomicSwap](#zgc.bep3.v1beta1.MsgClaimAtomicSwap)
    - [MsgClaimAtomicSwapResponse](#zgc.bep3.v1beta1.MsgClaimAtomicSwapResponse)
    - [MsgCreateAtomicSwap](#zgc.bep3.v1beta1.MsgCreateAtomicSwap)
    - [MsgCreateAtomicSwapResponse](#zgc.bep3.v1beta1.MsgCreateAtomicSwapResponse)
    - [MsgRefundAtomicSwap](#zgc.bep3.v1beta1.MsgRefundAtomicSwap)
    - [MsgRefundAtomicSwapResponse](#zgc.bep3.v1beta1.MsgRefundAtomicSwapResponse)
  
    - [Msg](#zgc.bep3.v1beta1.Msg)
  
- [zgc/committee/v1beta1/committee.proto](#zgc/committee/v1beta1/committee.proto)
    - [BaseCommittee](#zgc.committee.v1beta1.BaseCommittee)
    - [MemberCommittee](#zgc.committee.v1beta1.MemberCommittee)
    - [TokenCommittee](#zgc.committee.v1beta1.TokenCommittee)
  
    - [TallyOption](#zgc.committee.v1beta1.TallyOption)
  
- [zgc/committee/v1beta1/genesis.proto](#zgc/committee/v1beta1/genesis.proto)
    - [GenesisState](#zgc.committee.v1beta1.GenesisState)
    - [Proposal](#zgc.committee.v1beta1.Proposal)
    - [Vote](#zgc.committee.v1beta1.Vote)
  
    - [VoteType](#zgc.committee.v1beta1.VoteType)
  
- [zgc/committee/v1beta1/permissions.proto](#zgc/committee/v1beta1/permissions.proto)
    - [AllowedParamsChange](#zgc.committee.v1beta1.AllowedParamsChange)
    - [CommunityCDPRepayDebtPermission](#zgc.committee.v1beta1.CommunityCDPRepayDebtPermission)
    - [CommunityCDPWithdrawCollateralPermission](#zgc.committee.v1beta1.CommunityCDPWithdrawCollateralPermission)
    - [CommunityPoolLendWithdrawPermission](#zgc.committee.v1beta1.CommunityPoolLendWithdrawPermission)
    - [GodPermission](#zgc.committee.v1beta1.GodPermission)
    - [ParamsChangePermission](#zgc.committee.v1beta1.ParamsChangePermission)
    - [SoftwareUpgradePermission](#zgc.committee.v1beta1.SoftwareUpgradePermission)
    - [SubparamRequirement](#zgc.committee.v1beta1.SubparamRequirement)
    - [TextPermission](#zgc.committee.v1beta1.TextPermission)
  
- [zgc/committee/v1beta1/proposal.proto](#zgc/committee/v1beta1/proposal.proto)
    - [CommitteeChangeProposal](#zgc.committee.v1beta1.CommitteeChangeProposal)
    - [CommitteeDeleteProposal](#zgc.committee.v1beta1.CommitteeDeleteProposal)
  
- [zgc/committee/v1beta1/query.proto](#zgc/committee/v1beta1/query.proto)
    - [QueryCommitteeRequest](#zgc.committee.v1beta1.QueryCommitteeRequest)
    - [QueryCommitteeResponse](#zgc.committee.v1beta1.QueryCommitteeResponse)
    - [QueryCommitteesRequest](#zgc.committee.v1beta1.QueryCommitteesRequest)
    - [QueryCommitteesResponse](#zgc.committee.v1beta1.QueryCommitteesResponse)
    - [QueryNextProposalIDRequest](#zgc.committee.v1beta1.QueryNextProposalIDRequest)
    - [QueryNextProposalIDResponse](#zgc.committee.v1beta1.QueryNextProposalIDResponse)
    - [QueryProposalRequest](#zgc.committee.v1beta1.QueryProposalRequest)
    - [QueryProposalResponse](#zgc.committee.v1beta1.QueryProposalResponse)
    - [QueryProposalsRequest](#zgc.committee.v1beta1.QueryProposalsRequest)
    - [QueryProposalsResponse](#zgc.committee.v1beta1.QueryProposalsResponse)
    - [QueryRawParamsRequest](#zgc.committee.v1beta1.QueryRawParamsRequest)
    - [QueryRawParamsResponse](#zgc.committee.v1beta1.QueryRawParamsResponse)
    - [QueryTallyRequest](#zgc.committee.v1beta1.QueryTallyRequest)
    - [QueryTallyResponse](#zgc.committee.v1beta1.QueryTallyResponse)
    - [QueryVoteRequest](#zgc.committee.v1beta1.QueryVoteRequest)
    - [QueryVoteResponse](#zgc.committee.v1beta1.QueryVoteResponse)
    - [QueryVotesRequest](#zgc.committee.v1beta1.QueryVotesRequest)
    - [QueryVotesResponse](#zgc.committee.v1beta1.QueryVotesResponse)
  
    - [Query](#zgc.committee.v1beta1.Query)
  
- [zgc/committee/v1beta1/tx.proto](#zgc/committee/v1beta1/tx.proto)
    - [MsgSubmitProposal](#zgc.committee.v1beta1.MsgSubmitProposal)
    - [MsgSubmitProposalResponse](#zgc.committee.v1beta1.MsgSubmitProposalResponse)
    - [MsgVote](#zgc.committee.v1beta1.MsgVote)
    - [MsgVoteResponse](#zgc.committee.v1beta1.MsgVoteResponse)
  
    - [Msg](#zgc.committee.v1beta1.Msg)
  
- [zgc/council/v1/genesis.proto](#zgc/council/v1/genesis.proto)
    - [Ballot](#zgc.council.v1.Ballot)
    - [Council](#zgc.council.v1.Council)
    - [GenesisState](#zgc.council.v1.GenesisState)
    - [Params](#zgc.council.v1.Params)
    - [Vote](#zgc.council.v1.Vote)
  
- [zgc/council/v1/query.proto](#zgc/council/v1/query.proto)
    - [QueryCurrentCouncilIDRequest](#zgc.council.v1.QueryCurrentCouncilIDRequest)
    - [QueryCurrentCouncilIDResponse](#zgc.council.v1.QueryCurrentCouncilIDResponse)
    - [QueryRegisteredVotersRequest](#zgc.council.v1.QueryRegisteredVotersRequest)
    - [QueryRegisteredVotersResponse](#zgc.council.v1.QueryRegisteredVotersResponse)
  
    - [Query](#zgc.council.v1.Query)
  
- [zgc/council/v1/tx.proto](#zgc/council/v1/tx.proto)
    - [MsgRegister](#zgc.council.v1.MsgRegister)
    - [MsgRegisterResponse](#zgc.council.v1.MsgRegisterResponse)
    - [MsgVote](#zgc.council.v1.MsgVote)
    - [MsgVoteResponse](#zgc.council.v1.MsgVoteResponse)
  
    - [Msg](#zgc.council.v1.Msg)
  
- [zgc/dasigners/v1/dasigners.proto](#zgc/dasigners/v1/dasigners.proto)
    - [Quorum](#zgc.dasigners.v1.Quorum)
    - [Quorums](#zgc.dasigners.v1.Quorums)
    - [Signer](#zgc.dasigners.v1.Signer)
  
- [zgc/dasigners/v1/genesis.proto](#zgc/dasigners/v1/genesis.proto)
    - [GenesisState](#zgc.dasigners.v1.GenesisState)
    - [Params](#zgc.dasigners.v1.Params)
  
- [zgc/dasigners/v1/query.proto](#zgc/dasigners/v1/query.proto)
    - [QueryAggregatePubkeyG1Request](#zgc.dasigners.v1.QueryAggregatePubkeyG1Request)
    - [QueryAggregatePubkeyG1Response](#zgc.dasigners.v1.QueryAggregatePubkeyG1Response)
    - [QueryEpochNumberRequest](#zgc.dasigners.v1.QueryEpochNumberRequest)
    - [QueryEpochNumberResponse](#zgc.dasigners.v1.QueryEpochNumberResponse)
    - [QueryEpochQuorumRequest](#zgc.dasigners.v1.QueryEpochQuorumRequest)
    - [QueryEpochQuorumResponse](#zgc.dasigners.v1.QueryEpochQuorumResponse)
    - [QueryEpochQuorumRowRequest](#zgc.dasigners.v1.QueryEpochQuorumRowRequest)
    - [QueryEpochQuorumRowResponse](#zgc.dasigners.v1.QueryEpochQuorumRowResponse)
    - [QueryQuorumCountRequest](#zgc.dasigners.v1.QueryQuorumCountRequest)
    - [QueryQuorumCountResponse](#zgc.dasigners.v1.QueryQuorumCountResponse)
    - [QuerySignerRequest](#zgc.dasigners.v1.QuerySignerRequest)
    - [QuerySignerResponse](#zgc.dasigners.v1.QuerySignerResponse)
  
    - [Query](#zgc.dasigners.v1.Query)
  
- [zgc/dasigners/v1/tx.proto](#zgc/dasigners/v1/tx.proto)
    - [MsgRegisterNextEpoch](#zgc.dasigners.v1.MsgRegisterNextEpoch)
    - [MsgRegisterNextEpochResponse](#zgc.dasigners.v1.MsgRegisterNextEpochResponse)
    - [MsgRegisterSigner](#zgc.dasigners.v1.MsgRegisterSigner)
    - [MsgRegisterSignerResponse](#zgc.dasigners.v1.MsgRegisterSignerResponse)
    - [MsgUpdateSocket](#zgc.dasigners.v1.MsgUpdateSocket)
    - [MsgUpdateSocketResponse](#zgc.dasigners.v1.MsgUpdateSocketResponse)
  
    - [Msg](#zgc.dasigners.v1.Msg)
  
- [zgc/evmutil/v1beta1/conversion_pair.proto](#zgc/evmutil/v1beta1/conversion_pair.proto)
    - [AllowedCosmosCoinERC20Token](#zgc.evmutil.v1beta1.AllowedCosmosCoinERC20Token)
    - [ConversionPair](#zgc.evmutil.v1beta1.ConversionPair)
  
- [zgc/evmutil/v1beta1/genesis.proto](#zgc/evmutil/v1beta1/genesis.proto)
    - [Account](#zgc.evmutil.v1beta1.Account)
    - [GenesisState](#zgc.evmutil.v1beta1.GenesisState)
    - [Params](#zgc.evmutil.v1beta1.Params)
  
- [zgc/evmutil/v1beta1/query.proto](#zgc/evmutil/v1beta1/query.proto)
    - [DeployedCosmosCoinContract](#zgc.evmutil.v1beta1.DeployedCosmosCoinContract)
    - [QueryDeployedCosmosCoinContractsRequest](#zgc.evmutil.v1beta1.QueryDeployedCosmosCoinContractsRequest)
    - [QueryDeployedCosmosCoinContractsResponse](#zgc.evmutil.v1beta1.QueryDeployedCosmosCoinContractsResponse)
    - [QueryParamsRequest](#zgc.evmutil.v1beta1.QueryParamsRequest)
    - [QueryParamsResponse](#zgc.evmutil.v1beta1.QueryParamsResponse)
  
    - [Query](#zgc.evmutil.v1beta1.Query)
  
- [zgc/evmutil/v1beta1/tx.proto](#zgc/evmutil/v1beta1/tx.proto)
    - [MsgConvertCoinToERC20](#zgc.evmutil.v1beta1.MsgConvertCoinToERC20)
    - [MsgConvertCoinToERC20Response](#zgc.evmutil.v1beta1.MsgConvertCoinToERC20Response)
    - [MsgConvertCosmosCoinFromERC20](#zgc.evmutil.v1beta1.MsgConvertCosmosCoinFromERC20)
    - [MsgConvertCosmosCoinFromERC20Response](#zgc.evmutil.v1beta1.MsgConvertCosmosCoinFromERC20Response)
    - [MsgConvertCosmosCoinToERC20](#zgc.evmutil.v1beta1.MsgConvertCosmosCoinToERC20)
    - [MsgConvertCosmosCoinToERC20Response](#zgc.evmutil.v1beta1.MsgConvertCosmosCoinToERC20Response)
    - [MsgConvertERC20ToCoin](#zgc.evmutil.v1beta1.MsgConvertERC20ToCoin)
    - [MsgConvertERC20ToCoinResponse](#zgc.evmutil.v1beta1.MsgConvertERC20ToCoinResponse)
  
    - [Msg](#zgc.evmutil.v1beta1.Msg)
  
- [zgc/issuance/v1beta1/genesis.proto](#zgc/issuance/v1beta1/genesis.proto)
    - [Asset](#zgc.issuance.v1beta1.Asset)
    - [AssetSupply](#zgc.issuance.v1beta1.AssetSupply)
    - [GenesisState](#zgc.issuance.v1beta1.GenesisState)
    - [Params](#zgc.issuance.v1beta1.Params)
    - [RateLimit](#zgc.issuance.v1beta1.RateLimit)
  
- [zgc/issuance/v1beta1/query.proto](#zgc/issuance/v1beta1/query.proto)
    - [QueryParamsRequest](#zgc.issuance.v1beta1.QueryParamsRequest)
    - [QueryParamsResponse](#zgc.issuance.v1beta1.QueryParamsResponse)
  
    - [Query](#zgc.issuance.v1beta1.Query)
  
- [zgc/issuance/v1beta1/tx.proto](#zgc/issuance/v1beta1/tx.proto)
    - [MsgBlockAddress](#zgc.issuance.v1beta1.MsgBlockAddress)
    - [MsgBlockAddressResponse](#zgc.issuance.v1beta1.MsgBlockAddressResponse)
    - [MsgIssueTokens](#zgc.issuance.v1beta1.MsgIssueTokens)
    - [MsgIssueTokensResponse](#zgc.issuance.v1beta1.MsgIssueTokensResponse)
    - [MsgRedeemTokens](#zgc.issuance.v1beta1.MsgRedeemTokens)
    - [MsgRedeemTokensResponse](#zgc.issuance.v1beta1.MsgRedeemTokensResponse)
    - [MsgSetPauseStatus](#zgc.issuance.v1beta1.MsgSetPauseStatus)
    - [MsgSetPauseStatusResponse](#zgc.issuance.v1beta1.MsgSetPauseStatusResponse)
    - [MsgUnblockAddress](#zgc.issuance.v1beta1.MsgUnblockAddress)
    - [MsgUnblockAddressResponse](#zgc.issuance.v1beta1.MsgUnblockAddressResponse)
  
    - [Msg](#zgc.issuance.v1beta1.Msg)
  
- [zgc/pricefeed/v1beta1/store.proto](#zgc/pricefeed/v1beta1/store.proto)
    - [CurrentPrice](#zgc.pricefeed.v1beta1.CurrentPrice)
    - [Market](#zgc.pricefeed.v1beta1.Market)
    - [Params](#zgc.pricefeed.v1beta1.Params)
    - [PostedPrice](#zgc.pricefeed.v1beta1.PostedPrice)
  
- [zgc/pricefeed/v1beta1/genesis.proto](#zgc/pricefeed/v1beta1/genesis.proto)
    - [GenesisState](#zgc.pricefeed.v1beta1.GenesisState)
  
- [zgc/pricefeed/v1beta1/query.proto](#zgc/pricefeed/v1beta1/query.proto)
    - [CurrentPriceResponse](#zgc.pricefeed.v1beta1.CurrentPriceResponse)
    - [MarketResponse](#zgc.pricefeed.v1beta1.MarketResponse)
    - [PostedPriceResponse](#zgc.pricefeed.v1beta1.PostedPriceResponse)
    - [QueryMarketsRequest](#zgc.pricefeed.v1beta1.QueryMarketsRequest)
    - [QueryMarketsResponse](#zgc.pricefeed.v1beta1.QueryMarketsResponse)
    - [QueryOraclesRequest](#zgc.pricefeed.v1beta1.QueryOraclesRequest)
    - [QueryOraclesResponse](#zgc.pricefeed.v1beta1.QueryOraclesResponse)
    - [QueryParamsRequest](#zgc.pricefeed.v1beta1.QueryParamsRequest)
    - [QueryParamsResponse](#zgc.pricefeed.v1beta1.QueryParamsResponse)
    - [QueryPriceRequest](#zgc.pricefeed.v1beta1.QueryPriceRequest)
    - [QueryPriceResponse](#zgc.pricefeed.v1beta1.QueryPriceResponse)
    - [QueryPricesRequest](#zgc.pricefeed.v1beta1.QueryPricesRequest)
    - [QueryPricesResponse](#zgc.pricefeed.v1beta1.QueryPricesResponse)
    - [QueryRawPricesRequest](#zgc.pricefeed.v1beta1.QueryRawPricesRequest)
    - [QueryRawPricesResponse](#zgc.pricefeed.v1beta1.QueryRawPricesResponse)
  
    - [Query](#zgc.pricefeed.v1beta1.Query)
  
- [zgc/pricefeed/v1beta1/tx.proto](#zgc/pricefeed/v1beta1/tx.proto)
    - [MsgPostPrice](#zgc.pricefeed.v1beta1.MsgPostPrice)
    - [MsgPostPriceResponse](#zgc.pricefeed.v1beta1.MsgPostPriceResponse)
  
    - [Msg](#zgc.pricefeed.v1beta1.Msg)
  
- [kava/validatorvesting/v1beta1/query.proto](#kava/validatorvesting/v1beta1/query.proto)
    - [QueryCirculatingSupplyHARDRequest](#kava.validatorvesting.v1beta1.QueryCirculatingSupplyHARDRequest)
    - [QueryCirculatingSupplyHARDResponse](#kava.validatorvesting.v1beta1.QueryCirculatingSupplyHARDResponse)
    - [QueryCirculatingSupplyRequest](#kava.validatorvesting.v1beta1.QueryCirculatingSupplyRequest)
    - [QueryCirculatingSupplyResponse](#kava.validatorvesting.v1beta1.QueryCirculatingSupplyResponse)
    - [QueryCirculatingSupplySWPRequest](#kava.validatorvesting.v1beta1.QueryCirculatingSupplySWPRequest)
    - [QueryCirculatingSupplySWPResponse](#kava.validatorvesting.v1beta1.QueryCirculatingSupplySWPResponse)
    - [QueryCirculatingSupplyUSDXRequest](#kava.validatorvesting.v1beta1.QueryCirculatingSupplyUSDXRequest)
    - [QueryCirculatingSupplyUSDXResponse](#kava.validatorvesting.v1beta1.QueryCirculatingSupplyUSDXResponse)
    - [QueryTotalSupplyHARDRequest](#kava.validatorvesting.v1beta1.QueryTotalSupplyHARDRequest)
    - [QueryTotalSupplyHARDResponse](#kava.validatorvesting.v1beta1.QueryTotalSupplyHARDResponse)
    - [QueryTotalSupplyRequest](#kava.validatorvesting.v1beta1.QueryTotalSupplyRequest)
    - [QueryTotalSupplyResponse](#kava.validatorvesting.v1beta1.QueryTotalSupplyResponse)
    - [QueryTotalSupplyUSDXRequest](#kava.validatorvesting.v1beta1.QueryTotalSupplyUSDXRequest)
    - [QueryTotalSupplyUSDXResponse](#kava.validatorvesting.v1beta1.QueryTotalSupplyUSDXResponse)
  
    - [Query](#kava.validatorvesting.v1beta1.Query)
  
- [Scalar Value Types](#scalar-value-types)



<a name="crypto/vrf/keys.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## crypto/vrf/keys.proto
Copyright Tharsis Labs Ltd.(Evmos)
SPDX-License-Identifier:ENCL-1.0(https://github.com/evmos/evmos/blob/main/LICENSE)


<a name="crypto.vrf.PrivKey"></a>

### PrivKey
PrivKey defines a type alias for an vrf.PrivateKey that implements
Vrf's PrivateKey interface.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `key` | [bytes](#bytes) |  | key is the private key in byte form |






<a name="crypto.vrf.PubKey"></a>

### PubKey
PubKey defines a type alias for an vrf.PublicKey that implements
Vrf's PubKey interface. It represents the 32-byte compressed public
key format.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `key` | [bytes](#bytes) |  | key is the public key in byte form |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/bep3/v1beta1/bep3.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/bep3/v1beta1/bep3.proto



<a name="zgc.bep3.v1beta1.AssetParam"></a>

### AssetParam
AssetParam defines parameters for each bep3 asset.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `denom` | [string](#string) |  | denom represents the denominatin for this asset |
| `coin_id` | [int64](#int64) |  | coin_id represents the registered coin type to use (https://github.com/satoshilabs/slips/blob/master/slip-0044.md) |
| `supply_limit` | [SupplyLimit](#zgc.bep3.v1beta1.SupplyLimit) |  | supply_limit defines the maximum supply allowed for the asset - a total or time based rate limit |
| `active` | [bool](#bool) |  | active specifies if the asset is live or paused |
| `deputy_address` | [bytes](#bytes) |  | deputy_address the 0g-chain address of the deputy |
| `fixed_fee` | [string](#string) |  | fixed_fee defines the fee for incoming swaps |
| `min_swap_amount` | [string](#string) |  | min_swap_amount defines the minimum amount able to be swapped in a single message |
| `max_swap_amount` | [string](#string) |  | max_swap_amount defines the maximum amount able to be swapped in a single message |
| `min_block_lock` | [uint64](#uint64) |  | min_block_lock defined the minimum blocks to lock |
| `max_block_lock` | [uint64](#uint64) |  | min_block_lock defined the maximum blocks to lock |






<a name="zgc.bep3.v1beta1.AssetSupply"></a>

### AssetSupply
AssetSupply defines information about an asset's supply.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `incoming_supply` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | incoming_supply represents the incoming supply of an asset |
| `outgoing_supply` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | outgoing_supply represents the outgoing supply of an asset |
| `current_supply` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | current_supply represents the current on-chain supply of an asset |
| `time_limited_current_supply` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | time_limited_current_supply represents the time limited current supply of an asset |
| `time_elapsed` | [google.protobuf.Duration](#google.protobuf.Duration) |  | time_elapsed represents the time elapsed |






<a name="zgc.bep3.v1beta1.AtomicSwap"></a>

### AtomicSwap
AtomicSwap defines an atomic swap between chains for the pricefeed module.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) | repeated | amount represents the amount being swapped |
| `random_number_hash` | [bytes](#bytes) |  | random_number_hash represents the hash of the random number |
| `expire_height` | [uint64](#uint64) |  | expire_height represents the height when the swap expires |
| `timestamp` | [int64](#int64) |  | timestamp represents the timestamp of the swap |
| `sender` | [bytes](#bytes) |  | sender is the 0g-chain sender of the swap |
| `recipient` | [bytes](#bytes) |  | recipient is the 0g-chain recipient of the swap |
| `sender_other_chain` | [string](#string) |  | sender_other_chain is the sender on the other chain |
| `recipient_other_chain` | [string](#string) |  | recipient_other_chain is the recipient on the other chain |
| `closed_block` | [int64](#int64) |  | closed_block is the block when the swap is closed |
| `status` | [SwapStatus](#zgc.bep3.v1beta1.SwapStatus) |  | status represents the current status of the swap |
| `cross_chain` | [bool](#bool) |  | cross_chain identifies whether the atomic swap is cross chain |
| `direction` | [SwapDirection](#zgc.bep3.v1beta1.SwapDirection) |  | direction identifies if the swap is incoming or outgoing |






<a name="zgc.bep3.v1beta1.Params"></a>

### Params
Params defines the parameters for the bep3 module.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `asset_params` | [AssetParam](#zgc.bep3.v1beta1.AssetParam) | repeated | asset_params define the parameters for each bep3 asset |






<a name="zgc.bep3.v1beta1.SupplyLimit"></a>

### SupplyLimit
SupplyLimit define the absolute and time-based limits for an assets's supply.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `limit` | [string](#string) |  | limit defines the total supply allowed |
| `time_limited` | [bool](#bool) |  | time_limited enables or disables time based supply limiting |
| `time_period` | [google.protobuf.Duration](#google.protobuf.Duration) |  | time_period specifies the duration that time_based_limit is evalulated |
| `time_based_limit` | [string](#string) |  | time_based_limit defines the maximum supply that can be swapped within time_period |





 <!-- end messages -->


<a name="zgc.bep3.v1beta1.SwapDirection"></a>

### SwapDirection
SwapDirection is the direction of an AtomicSwap

| Name | Number | Description |
| ---- | ------ | ----------- |
| SWAP_DIRECTION_UNSPECIFIED | 0 | SWAP_DIRECTION_UNSPECIFIED represents unspecified or invalid swap direcation |
| SWAP_DIRECTION_INCOMING | 1 | SWAP_DIRECTION_INCOMING represents is incoming swap (to the 0g-chain) |
| SWAP_DIRECTION_OUTGOING | 2 | SWAP_DIRECTION_OUTGOING represents an outgoing swap (from the 0g-chain) |



<a name="zgc.bep3.v1beta1.SwapStatus"></a>

### SwapStatus
SwapStatus is the status of an AtomicSwap

| Name | Number | Description |
| ---- | ------ | ----------- |
| SWAP_STATUS_UNSPECIFIED | 0 | SWAP_STATUS_UNSPECIFIED represents an unspecified status |
| SWAP_STATUS_OPEN | 1 | SWAP_STATUS_OPEN represents an open swap |
| SWAP_STATUS_COMPLETED | 2 | SWAP_STATUS_COMPLETED represents a completed swap |
| SWAP_STATUS_EXPIRED | 3 | SWAP_STATUS_EXPIRED represents an expired swap |


 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/bep3/v1beta1/genesis.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/bep3/v1beta1/genesis.proto



<a name="zgc.bep3.v1beta1.GenesisState"></a>

### GenesisState
GenesisState defines the pricefeed module's genesis state.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#kava.bep3.v1beta1.Params) |  | params defines all the parameters of the module. |
| `atomic_swaps` | [AtomicSwap](#kava.bep3.v1beta1.AtomicSwap) | repeated | atomic_swaps represents the state of stored atomic swaps |
| `supplies` | [AssetSupply](#kava.bep3.v1beta1.AssetSupply) | repeated | supplies represents the supply information of each atomic swap |
| `previous_block_time` | [google.protobuf.Timestamp](#google.protobuf.Timestamp) |  | previous_block_time represents the time of the previous block |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/bep3/v1beta1/query.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/bep3/v1beta1/query.proto



<a name="zgc.bep3.v1beta1.AssetSupplyResponse"></a>

### AssetSupplyResponse
AssetSupplyResponse defines information about an asset's supply.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `incoming_supply` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | incoming_supply represents the incoming supply of an asset |
| `outgoing_supply` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | outgoing_supply represents the outgoing supply of an asset |
| `current_supply` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | current_supply represents the current on-chain supply of an asset |
| `time_limited_current_supply` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | time_limited_current_supply represents the time limited current supply of an asset |
| `time_elapsed` | [google.protobuf.Duration](#google.protobuf.Duration) |  | time_elapsed represents the time elapsed |






<a name="zgc.bep3.v1beta1.AtomicSwapResponse"></a>

### AtomicSwapResponse
AtomicSwapResponse represents the returned atomic swap properties


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `id` | [string](#string) |  | id represents the id of the atomic swap |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) | repeated | amount represents the amount being swapped |
| `random_number_hash` | [string](#string) |  | random_number_hash represents the hash of the random number |
| `expire_height` | [uint64](#uint64) |  | expire_height represents the height when the swap expires |
| `timestamp` | [int64](#int64) |  | timestamp represents the timestamp of the swap |
| `sender` | [string](#string) |  | sender is the 0g-chain sender of the swap |
| `recipient` | [string](#string) |  | recipient is the 0g-chain recipient of the swap |
| `sender_other_chain` | [string](#string) |  | sender_other_chain is the sender on the other chain |
| `recipient_other_chain` | [string](#string) |  | recipient_other_chain is the recipient on the other chain |
| `closed_block` | [int64](#int64) |  | closed_block is the block when the swap is closed |
| `status` | [SwapStatus](#zgc.bep3.v1beta1.SwapStatus) |  | status represents the current status of the swap |
| `cross_chain` | [bool](#bool) |  | cross_chain identifies whether the atomic swap is cross chain |
| `direction` | [SwapDirection](#zgc.bep3.v1beta1.SwapDirection) |  | direction identifies if the swap is incoming or outgoing |






<a name="zgc.bep3.v1beta1.QueryAssetSuppliesRequest"></a>

### QueryAssetSuppliesRequest
QueryAssetSuppliesRequest is the request type for the Query/AssetSupplies RPC method.






<a name="zgc.bep3.v1beta1.QueryAssetSuppliesResponse"></a>

### QueryAssetSuppliesResponse
QueryAssetSuppliesResponse is the response type for the Query/AssetSupplies RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `asset_supplies` | [AssetSupplyResponse](#zgc.bep3.v1beta1.AssetSupplyResponse) | repeated | asset_supplies represents the supplies of returned assets |






<a name="zgc.bep3.v1beta1.QueryAssetSupplyRequest"></a>

### QueryAssetSupplyRequest
QueryAssetSupplyRequest is the request type for the Query/AssetSupply RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `denom` | [string](#string) |  | denom filters the asset response for the specified denom |






<a name="zgc.bep3.v1beta1.QueryAssetSupplyResponse"></a>

### QueryAssetSupplyResponse
QueryAssetSupplyResponse is the response type for the Query/AssetSupply RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `asset_supply` | [AssetSupplyResponse](#zgc.bep3.v1beta1.AssetSupplyResponse) |  | asset_supply represents the supply of the asset |






<a name="zgc.bep3.v1beta1.QueryAtomicSwapRequest"></a>

### QueryAtomicSwapRequest
QueryAtomicSwapRequest is the request type for the Query/AtomicSwap RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `swap_id` | [string](#string) |  | swap_id represents the id of the swap to query |






<a name="zgc.bep3.v1beta1.QueryAtomicSwapResponse"></a>

### QueryAtomicSwapResponse
QueryAtomicSwapResponse is the response type for the Query/AtomicSwap RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `atomic_swap` | [AtomicSwapResponse](#zgc.bep3.v1beta1.AtomicSwapResponse) |  |  |






<a name="zgc.bep3.v1beta1.QueryAtomicSwapsRequest"></a>

### QueryAtomicSwapsRequest
QueryAtomicSwapsRequest is the request type for the Query/AtomicSwaps RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `involve` | [string](#string) |  | involve filters by address |
| `expiration` | [uint64](#uint64) |  | expiration filters by expiration block height |
| `status` | [SwapStatus](#zgc.bep3.v1beta1.SwapStatus) |  | status filters by swap status |
| `direction` | [SwapDirection](#zgc.bep3.v1beta1.SwapDirection) |  | direction fitlers by swap direction |
| `pagination` | [cosmos.base.query.v1beta1.PageRequest](#cosmos.base.query.v1beta1.PageRequest) |  |  |






<a name="zgc.bep3.v1beta1.QueryAtomicSwapsResponse"></a>

### QueryAtomicSwapsResponse
QueryAtomicSwapsResponse is the response type for the Query/AtomicSwaps RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `atomic_swaps` | [AtomicSwapResponse](#zgc.bep3.v1beta1.AtomicSwapResponse) | repeated | atomic_swap represents the returned atomic swaps for the request |
| `pagination` | [cosmos.base.query.v1beta1.PageResponse](#cosmos.base.query.v1beta1.PageResponse) |  |  |






<a name="zgc.bep3.v1beta1.QueryParamsRequest"></a>

### QueryParamsRequest
QueryParamsRequest defines the request type for querying x/bep3 parameters.






<a name="zgc.bep3.v1beta1.QueryParamsResponse"></a>

### QueryParamsResponse
QueryParamsResponse defines the response type for querying x/bep3 parameters.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#zgc.bep3.v1beta1.Params) |  | params represents the parameters of the module |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.bep3.v1beta1.Query"></a>

### Query
Query defines the gRPC querier service for bep3 module

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `Params` | [QueryParamsRequest](#zgc.bep3.v1beta1.QueryParamsRequest) | [QueryParamsResponse](#zgc.bep3.v1beta1.QueryParamsResponse) | Params queries module params | GET|/0g/bep3/v1beta1/params|
| `AssetSupply` | [QueryAssetSupplyRequest](#zgc.bep3.v1beta1.QueryAssetSupplyRequest) | [QueryAssetSupplyResponse](#zgc.bep3.v1beta1.QueryAssetSupplyResponse) | AssetSupply queries info about an asset's supply | GET|/0g/bep3/v1beta1/assetsupply/{denom}|
| `AssetSupplies` | [QueryAssetSuppliesRequest](#zgc.bep3.v1beta1.QueryAssetSuppliesRequest) | [QueryAssetSuppliesResponse](#zgc.bep3.v1beta1.QueryAssetSuppliesResponse) | AssetSupplies queries a list of asset supplies | GET|/0g/bep3/v1beta1/assetsupplies|
| `AtomicSwap` | [QueryAtomicSwapRequest](#zgc.bep3.v1beta1.QueryAtomicSwapRequest) | [QueryAtomicSwapResponse](#zgc.bep3.v1beta1.QueryAtomicSwapResponse) | AtomicSwap queries info about an atomic swap | GET|/0g/bep3/v1beta1/atomicswap/{swap_id}|
| `AtomicSwaps` | [QueryAtomicSwapsRequest](#zgc.bep3.v1beta1.QueryAtomicSwapsRequest) | [QueryAtomicSwapsResponse](#zgc.bep3.v1beta1.QueryAtomicSwapsResponse) | AtomicSwaps queries a list of atomic swaps | GET|/0g/bep3/v1beta1/atomicswaps|

 <!-- end services -->



<a name="zgc/bep3/v1beta1/tx.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/bep3/v1beta1/tx.proto



<a name="zgc.bep3.v1beta1.MsgClaimAtomicSwap"></a>

### MsgClaimAtomicSwap
MsgClaimAtomicSwap defines the Msg/ClaimAtomicSwap request type.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `from` | [string](#string) |  |  |
| `swap_id` | [string](#string) |  |  |
| `random_number` | [string](#string) |  |  |






<a name="zgc.bep3.v1beta1.MsgClaimAtomicSwapResponse"></a>

### MsgClaimAtomicSwapResponse
MsgClaimAtomicSwapResponse defines the Msg/ClaimAtomicSwap response type.






<a name="zgc.bep3.v1beta1.MsgCreateAtomicSwap"></a>

### MsgCreateAtomicSwap
MsgCreateAtomicSwap defines the Msg/CreateAtomicSwap request type.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `from` | [string](#string) |  |  |
| `to` | [string](#string) |  |  |
| `recipient_other_chain` | [string](#string) |  |  |
| `sender_other_chain` | [string](#string) |  |  |
| `random_number_hash` | [string](#string) |  |  |
| `timestamp` | [int64](#int64) |  |  |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) | repeated |  |
| `height_span` | [uint64](#uint64) |  |  |






<a name="zgc.bep3.v1beta1.MsgCreateAtomicSwapResponse"></a>

### MsgCreateAtomicSwapResponse
MsgCreateAtomicSwapResponse defines the Msg/CreateAtomicSwap response type.






<a name="zgc.bep3.v1beta1.MsgRefundAtomicSwap"></a>

### MsgRefundAtomicSwap
MsgRefundAtomicSwap defines the Msg/RefundAtomicSwap request type.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `from` | [string](#string) |  |  |
| `swap_id` | [string](#string) |  |  |






<a name="zgc.bep3.v1beta1.MsgRefundAtomicSwapResponse"></a>

### MsgRefundAtomicSwapResponse
MsgRefundAtomicSwapResponse defines the Msg/RefundAtomicSwap response type.





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.bep3.v1beta1.Msg"></a>

### Msg
Msg defines the bep3 Msg service.

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `CreateAtomicSwap` | [MsgCreateAtomicSwap](#zgc.bep3.v1beta1.MsgCreateAtomicSwap) | [MsgCreateAtomicSwapResponse](#zgc.bep3.v1beta1.MsgCreateAtomicSwapResponse) | CreateAtomicSwap defines a method for creating an atomic swap | |
| `ClaimAtomicSwap` | [MsgClaimAtomicSwap](#zgc.bep3.v1beta1.MsgClaimAtomicSwap) | [MsgClaimAtomicSwapResponse](#zgc.bep3.v1beta1.MsgClaimAtomicSwapResponse) | ClaimAtomicSwap defines a method for claiming an atomic swap | |
| `RefundAtomicSwap` | [MsgRefundAtomicSwap](#zgc.bep3.v1beta1.MsgRefundAtomicSwap) | [MsgRefundAtomicSwapResponse](#zgc.bep3.v1beta1.MsgRefundAtomicSwapResponse) | RefundAtomicSwap defines a method for refunding an atomic swap | |

 <!-- end services -->



<a name="zgc/committee/v1beta1/committee.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/committee/v1beta1/committee.proto



<a name="kava.cdp.v1beta1.CDP"></a>

### CDP
CDP defines the state of a single collateralized debt position.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `id` | [uint64](#uint64) |  |  |
| `owner` | [bytes](#bytes) |  |  |
| `type` | [string](#string) |  |  |
| `collateral` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `principal` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `accumulated_fees` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `fees_updated` | [google.protobuf.Timestamp](#google.protobuf.Timestamp) |  |  |
| `interest_factor` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.Deposit"></a>

### Deposit
Deposit defines an amount of coins deposited by an account to a cdp


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `cdp_id` | [uint64](#uint64) |  |  |
| `depositor` | [string](#string) |  |  |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |






<a name="kava.cdp.v1beta1.OwnerCDPIndex"></a>

### OwnerCDPIndex
OwnerCDPIndex defines the cdp ids for a single cdp owner


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `cdp_ids` | [uint64](#uint64) | repeated |  |






<a name="kava.cdp.v1beta1.TotalCollateral"></a>

### TotalCollateral
TotalCollateral defines the total collateral of a given collateral type


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `collateral_type` | [string](#string) |  |  |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |






<a name="kava.cdp.v1beta1.TotalPrincipal"></a>

### TotalPrincipal
TotalPrincipal defines the total principal of a given collateral type


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `collateral_type` | [string](#string) |  |  |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="kava/cdp/v1beta1/genesis.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/cdp/v1beta1/genesis.proto



<a name="kava.cdp.v1beta1.CollateralParam"></a>

### CollateralParam
CollateralParam defines governance parameters for each collateral type within the cdp module


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `denom` | [string](#string) |  |  |
| `type` | [string](#string) |  |  |
| `liquidation_ratio` | [string](#string) |  |  |
| `debt_limit` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `stability_fee` | [string](#string) |  |  |
| `auction_size` | [string](#string) |  |  |
| `liquidation_penalty` | [string](#string) |  |  |
| `spot_market_id` | [string](#string) |  |  |
| `liquidation_market_id` | [string](#string) |  |  |
| `keeper_reward_percentage` | [string](#string) |  |  |
| `check_collateralization_index_count` | [string](#string) |  |  |
| `conversion_factor` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.DebtParam"></a>

### DebtParam
DebtParam defines governance params for debt assets


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `denom` | [string](#string) |  |  |
| `reference_asset` | [string](#string) |  |  |
| `conversion_factor` | [string](#string) |  |  |
| `debt_floor` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.GenesisAccumulationTime"></a>

### GenesisAccumulationTime
GenesisAccumulationTime defines the previous distribution time and its corresponding denom


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `collateral_type` | [string](#string) |  |  |
| `previous_accumulation_time` | [google.protobuf.Timestamp](#google.protobuf.Timestamp) |  |  |
| `interest_factor` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.GenesisState"></a>

### GenesisState
GenesisState defines the cdp module's genesis state.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#kava.cdp.v1beta1.Params) |  | params defines all the parameters of the module. |
| `cdps` | [CDP](#kava.cdp.v1beta1.CDP) | repeated |  |
| `deposits` | [Deposit](#kava.cdp.v1beta1.Deposit) | repeated |  |
| `starting_cdp_id` | [uint64](#uint64) |  |  |
| `debt_denom` | [string](#string) |  |  |
| `gov_denom` | [string](#string) |  |  |
| `previous_accumulation_times` | [GenesisAccumulationTime](#kava.cdp.v1beta1.GenesisAccumulationTime) | repeated |  |
| `total_principals` | [GenesisTotalPrincipal](#kava.cdp.v1beta1.GenesisTotalPrincipal) | repeated |  |






<a name="kava.cdp.v1beta1.GenesisTotalPrincipal"></a>

### GenesisTotalPrincipal
GenesisTotalPrincipal defines the total principal and its corresponding collateral type


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `collateral_type` | [string](#string) |  |  |
| `total_principal` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.Params"></a>

### Params
Params defines the parameters for the cdp module.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `collateral_params` | [CollateralParam](#kava.cdp.v1beta1.CollateralParam) | repeated |  |
| `debt_param` | [DebtParam](#kava.cdp.v1beta1.DebtParam) |  |  |
| `global_debt_limit` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `surplus_auction_threshold` | [string](#string) |  |  |
| `surplus_auction_lot` | [string](#string) |  |  |
| `debt_auction_threshold` | [string](#string) |  |  |
| `debt_auction_lot` | [string](#string) |  |  |
| `circuit_breaker` | [bool](#bool) |  |  |
| `liquidation_block_interval` | [int64](#int64) |  |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="kava/cdp/v1beta1/query.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/cdp/v1beta1/query.proto



<a name="kava.cdp.v1beta1.CDPResponse"></a>

### CDPResponse
CDPResponse defines the state of a single collateralized debt position.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `id` | [uint64](#uint64) |  |  |
| `owner` | [string](#string) |  |  |
| `type` | [string](#string) |  |  |
| `collateral` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `principal` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `accumulated_fees` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `fees_updated` | [google.protobuf.Timestamp](#google.protobuf.Timestamp) |  |  |
| `interest_factor` | [string](#string) |  |  |
| `collateral_value` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `collateralization_ratio` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.QueryAccountsRequest"></a>

### QueryAccountsRequest
QueryAccountsRequest defines the request type for the Query/Accounts RPC method.






<a name="kava.cdp.v1beta1.QueryAccountsResponse"></a>

### QueryAccountsResponse
QueryAccountsResponse defines the response type for the Query/Accounts RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `accounts` | [cosmos.auth.v1beta1.ModuleAccount](#cosmos.auth.v1beta1.ModuleAccount) | repeated |  |






<a name="kava.cdp.v1beta1.QueryCdpRequest"></a>

### QueryCdpRequest
QueryCdpRequest defines the request type for the Query/Cdp RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `collateral_type` | [string](#string) |  |  |
| `owner` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.QueryCdpResponse"></a>

### QueryCdpResponse
QueryCdpResponse defines the response type for the Query/Cdp RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `cdp` | [CDPResponse](#kava.cdp.v1beta1.CDPResponse) |  |  |






<a name="kava.cdp.v1beta1.QueryCdpsRequest"></a>

### QueryCdpsRequest
QueryCdpsRequest is the params for a filtered CDP query, the request type for the Query/Cdps RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `collateral_type` | [string](#string) |  |  |
| `owner` | [string](#string) |  |  |
| `id` | [uint64](#uint64) |  |  |
| `ratio` | [string](#string) |  | sdk.Dec as a string |
| `pagination` | [cosmos.base.query.v1beta1.PageRequest](#cosmos.base.query.v1beta1.PageRequest) |  |  |






<a name="kava.cdp.v1beta1.QueryCdpsResponse"></a>

### QueryCdpsResponse
QueryCdpsResponse defines the response type for the Query/Cdps RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `cdps` | [CDPResponse](#kava.cdp.v1beta1.CDPResponse) | repeated |  |
| `pagination` | [cosmos.base.query.v1beta1.PageResponse](#cosmos.base.query.v1beta1.PageResponse) |  |  |






<a name="kava.cdp.v1beta1.QueryDepositsRequest"></a>

### QueryDepositsRequest
QueryDepositsRequest defines the request type for the Query/Deposits RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `collateral_type` | [string](#string) |  |  |
| `owner` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.QueryDepositsResponse"></a>

### QueryDepositsResponse
QueryDepositsResponse defines the response type for the Query/Deposits RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `deposits` | [Deposit](#kava.cdp.v1beta1.Deposit) | repeated |  |






<a name="kava.cdp.v1beta1.QueryParamsRequest"></a>

### QueryParamsRequest
QueryParamsRequest defines the request type for the Query/Params RPC method.






<a name="kava.cdp.v1beta1.QueryParamsResponse"></a>

### QueryParamsResponse
QueryParamsResponse defines the response type for the Query/Params RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#kava.cdp.v1beta1.Params) |  |  |






<a name="kava.cdp.v1beta1.QueryTotalCollateralRequest"></a>

### QueryTotalCollateralRequest
QueryTotalCollateralRequest defines the request type for the Query/TotalCollateral RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `collateral_type` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.QueryTotalCollateralResponse"></a>

### QueryTotalCollateralResponse
QueryTotalCollateralResponse defines the response type for the Query/TotalCollateral RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `total_collateral` | [TotalCollateral](#kava.cdp.v1beta1.TotalCollateral) | repeated |  |






<a name="kava.cdp.v1beta1.QueryTotalPrincipalRequest"></a>

### QueryTotalPrincipalRequest
QueryTotalPrincipalRequest defines the request type for the Query/TotalPrincipal RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `collateral_type` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.QueryTotalPrincipalResponse"></a>

### QueryTotalPrincipalResponse
QueryTotalPrincipalResponse defines the response type for the Query/TotalPrincipal RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `total_principal` | [TotalPrincipal](#kava.cdp.v1beta1.TotalPrincipal) | repeated |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="kava.cdp.v1beta1.Query"></a>

### Query
Query defines the gRPC querier service for cdp module

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `Params` | [QueryParamsRequest](#kava.cdp.v1beta1.QueryParamsRequest) | [QueryParamsResponse](#kava.cdp.v1beta1.QueryParamsResponse) | Params queries all parameters of the cdp module. | GET|/kava/cdp/v1beta1/params|
| `Accounts` | [QueryAccountsRequest](#kava.cdp.v1beta1.QueryAccountsRequest) | [QueryAccountsResponse](#kava.cdp.v1beta1.QueryAccountsResponse) | Accounts queries the CDP module accounts. | GET|/kava/cdp/v1beta1/accounts|
| `TotalPrincipal` | [QueryTotalPrincipalRequest](#kava.cdp.v1beta1.QueryTotalPrincipalRequest) | [QueryTotalPrincipalResponse](#kava.cdp.v1beta1.QueryTotalPrincipalResponse) | TotalPrincipal queries the total principal of a given collateral type. | GET|/kava/cdp/v1beta1/totalPrincipal|
| `TotalCollateral` | [QueryTotalCollateralRequest](#kava.cdp.v1beta1.QueryTotalCollateralRequest) | [QueryTotalCollateralResponse](#kava.cdp.v1beta1.QueryTotalCollateralResponse) | TotalCollateral queries the total collateral of a given collateral type. | GET|/kava/cdp/v1beta1/totalCollateral|
| `Cdps` | [QueryCdpsRequest](#kava.cdp.v1beta1.QueryCdpsRequest) | [QueryCdpsResponse](#kava.cdp.v1beta1.QueryCdpsResponse) | Cdps queries all active CDPs. | GET|/kava/cdp/v1beta1/cdps|
| `Cdp` | [QueryCdpRequest](#kava.cdp.v1beta1.QueryCdpRequest) | [QueryCdpResponse](#kava.cdp.v1beta1.QueryCdpResponse) | Cdp queries a CDP with the input owner address and collateral type. | GET|/kava/cdp/v1beta1/cdps/{owner}/{collateral_type}|
| `Deposits` | [QueryDepositsRequest](#kava.cdp.v1beta1.QueryDepositsRequest) | [QueryDepositsResponse](#kava.cdp.v1beta1.QueryDepositsResponse) | Deposits queries deposits associated with the CDP owned by an address for a collateral type. | GET|/kava/cdp/v1beta1/cdps/deposits/{owner}/{collateral_type}|

 <!-- end services -->



<a name="kava/cdp/v1beta1/tx.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/cdp/v1beta1/tx.proto



<a name="kava.cdp.v1beta1.MsgCreateCDP"></a>

### MsgCreateCDP
MsgCreateCDP defines a message to create a new CDP.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `sender` | [string](#string) |  |  |
| `collateral` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `principal` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `collateral_type` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.MsgCreateCDPResponse"></a>

### MsgCreateCDPResponse
MsgCreateCDPResponse defines the Msg/CreateCDP response type.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `cdp_id` | [uint64](#uint64) |  |  |






<a name="kava.cdp.v1beta1.MsgDeposit"></a>

### MsgDeposit
MsgDeposit defines a message to deposit to a CDP.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `depositor` | [string](#string) |  |  |
| `owner` | [string](#string) |  |  |
| `collateral` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `collateral_type` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.MsgDepositResponse"></a>

### MsgDepositResponse
MsgDepositResponse defines the Msg/Deposit response type.






<a name="kava.cdp.v1beta1.MsgDrawDebt"></a>

### MsgDrawDebt
MsgDrawDebt defines a message to draw debt from a CDP.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `sender` | [string](#string) |  |  |
| `collateral_type` | [string](#string) |  |  |
| `principal` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |






<a name="kava.cdp.v1beta1.MsgDrawDebtResponse"></a>

### MsgDrawDebtResponse
MsgDrawDebtResponse defines the Msg/DrawDebt response type.






<a name="kava.cdp.v1beta1.MsgLiquidate"></a>

### MsgLiquidate
MsgLiquidate defines a message to attempt to liquidate a CDP whos
collateralization ratio is under its liquidation ratio.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `keeper` | [string](#string) |  |  |
| `borrower` | [string](#string) |  |  |
| `collateral_type` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.MsgLiquidateResponse"></a>

### MsgLiquidateResponse
MsgLiquidateResponse defines the Msg/Liquidate response type.






<a name="kava.cdp.v1beta1.MsgRepayDebt"></a>

### MsgRepayDebt
MsgRepayDebt defines a message to repay debt from a CDP.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `sender` | [string](#string) |  |  |
| `collateral_type` | [string](#string) |  |  |
| `payment` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |






<a name="kava.cdp.v1beta1.MsgRepayDebtResponse"></a>

### MsgRepayDebtResponse
MsgRepayDebtResponse defines the Msg/RepayDebt response type.






<a name="kava.cdp.v1beta1.MsgWithdraw"></a>

### MsgWithdraw
MsgWithdraw defines a message to withdraw collateral from a CDP.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `depositor` | [string](#string) |  |  |
| `owner` | [string](#string) |  |  |
| `collateral` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `collateral_type` | [string](#string) |  |  |






<a name="kava.cdp.v1beta1.MsgWithdrawResponse"></a>

### MsgWithdrawResponse
MsgWithdrawResponse defines the Msg/Withdraw response type.





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="kava.cdp.v1beta1.Msg"></a>

### Msg
Msg defines the cdp Msg service.

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `CreateCDP` | [MsgCreateCDP](#kava.cdp.v1beta1.MsgCreateCDP) | [MsgCreateCDPResponse](#kava.cdp.v1beta1.MsgCreateCDPResponse) | CreateCDP defines a method to create a new CDP. | |
| `Deposit` | [MsgDeposit](#kava.cdp.v1beta1.MsgDeposit) | [MsgDepositResponse](#kava.cdp.v1beta1.MsgDepositResponse) | Deposit defines a method to deposit to a CDP. | |
| `Withdraw` | [MsgWithdraw](#kava.cdp.v1beta1.MsgWithdraw) | [MsgWithdrawResponse](#kava.cdp.v1beta1.MsgWithdrawResponse) | Withdraw defines a method to withdraw collateral from a CDP. | |
| `DrawDebt` | [MsgDrawDebt](#kava.cdp.v1beta1.MsgDrawDebt) | [MsgDrawDebtResponse](#kava.cdp.v1beta1.MsgDrawDebtResponse) | DrawDebt defines a method to draw debt from a CDP. | |
| `RepayDebt` | [MsgRepayDebt](#kava.cdp.v1beta1.MsgRepayDebt) | [MsgRepayDebtResponse](#kava.cdp.v1beta1.MsgRepayDebtResponse) | RepayDebt defines a method to repay debt from a CDP. | |
| `Liquidate` | [MsgLiquidate](#kava.cdp.v1beta1.MsgLiquidate) | [MsgLiquidateResponse](#kava.cdp.v1beta1.MsgLiquidateResponse) | Liquidate defines a method to attempt to liquidate a CDP whos collateralization ratio is under its liquidation ratio. | |

 <!-- end services -->



<a name="kava/committee/v1beta1/committee.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/committee/v1beta1/committee.proto



<a name="kava.committee.v1beta1.BaseCommittee"></a>

### BaseCommittee
BaseCommittee is a common type shared by all Committees


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `id` | [uint64](#uint64) |  |  |
| `description` | [string](#string) |  |  |
| `members` | [bytes](#bytes) | repeated |  |
| `permissions` | [google.protobuf.Any](#google.protobuf.Any) | repeated |  |
| `vote_threshold` | [string](#string) |  | Smallest percentage that must vote for a proposal to pass |
| `proposal_duration` | [google.protobuf.Duration](#google.protobuf.Duration) |  | The length of time a proposal remains active for. Proposals will close earlier if they get enough votes. |
| `tally_option` | [TallyOption](#zgc.committee.v1beta1.TallyOption) |  |  |






<a name="zgc.committee.v1beta1.MemberCommittee"></a>

### MemberCommittee
MemberCommittee is an alias of BaseCommittee


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `base_committee` | [BaseCommittee](#zgc.committee.v1beta1.BaseCommittee) |  |  |






<a name="zgc.committee.v1beta1.TokenCommittee"></a>

### TokenCommittee
TokenCommittee supports voting on proposals by token holders


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `base_committee` | [BaseCommittee](#zgc.committee.v1beta1.BaseCommittee) |  |  |
| `quorum` | [string](#string) |  |  |
| `tally_denom` | [string](#string) |  |  |





 <!-- end messages -->


<a name="zgc.committee.v1beta1.TallyOption"></a>

### TallyOption
TallyOption enumerates the valid types of a tally.

| Name | Number | Description |
| ---- | ------ | ----------- |
| TALLY_OPTION_UNSPECIFIED | 0 | TALLY_OPTION_UNSPECIFIED defines a null tally option. |
| TALLY_OPTION_FIRST_PAST_THE_POST | 1 | Votes are tallied each block and the proposal passes as soon as the vote threshold is reached |
| TALLY_OPTION_DEADLINE | 2 | Votes are tallied exactly once, when the deadline time is reached |


 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/committee/v1beta1/genesis.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/committee/v1beta1/genesis.proto



<a name="zgc.committee.v1beta1.GenesisState"></a>

### GenesisState
GenesisState defines the committee module's genesis state.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `next_proposal_id` | [uint64](#uint64) |  |  |
| `committees` | [google.protobuf.Any](#google.protobuf.Any) | repeated |  |
| `proposals` | [Proposal](#zgc.committee.v1beta1.Proposal) | repeated |  |
| `votes` | [Vote](#zgc.committee.v1beta1.Vote) | repeated |  |






<a name="zgc.committee.v1beta1.Proposal"></a>

### Proposal
Proposal is an internal record of a governance proposal submitted to a committee.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `content` | [google.protobuf.Any](#google.protobuf.Any) |  |  |
| `id` | [uint64](#uint64) |  |  |
| `committee_id` | [uint64](#uint64) |  |  |
| `deadline` | [google.protobuf.Timestamp](#google.protobuf.Timestamp) |  |  |






<a name="zgc.committee.v1beta1.Vote"></a>

### Vote
Vote is an internal record of a single governance vote.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `proposal_id` | [uint64](#uint64) |  |  |
| `voter` | [bytes](#bytes) |  |  |
| `vote_type` | [VoteType](#zgc.committee.v1beta1.VoteType) |  |  |





 <!-- end messages -->


<a name="zgc.committee.v1beta1.VoteType"></a>

### VoteType
VoteType enumerates the valid types of a vote.

| Name | Number | Description |
| ---- | ------ | ----------- |
| VOTE_TYPE_UNSPECIFIED | 0 | VOTE_TYPE_UNSPECIFIED defines a no-op vote option. |
| VOTE_TYPE_YES | 1 | VOTE_TYPE_YES defines a yes vote option. |
| VOTE_TYPE_NO | 2 | VOTE_TYPE_NO defines a no vote option. |
| VOTE_TYPE_ABSTAIN | 3 | VOTE_TYPE_ABSTAIN defines an abstain vote option. |


 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/committee/v1beta1/permissions.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/committee/v1beta1/permissions.proto



<a name="zgc.committee.v1beta1.AllowedParamsChange"></a>

### AllowedParamsChange
AllowedParamsChange contains data on the allowed parameter changes for subspace, key, and sub params requirements.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `subspace` | [string](#string) |  |  |
| `key` | [string](#string) |  |  |
| `single_subparam_allowed_attrs` | [string](#string) | repeated | Requirements for when the subparam value is a single record. This contains list of allowed attribute keys that can be changed on the subparam record. |
| `multi_subparams_requirements` | [SubparamRequirement](#zgc.committee.v1beta1.SubparamRequirement) | repeated | Requirements for when the subparam value is a list of records. The requirements contains requirements for each record in the list. |






<a name="zgc.committee.v1beta1.CommunityCDPRepayDebtPermission"></a>

### CommunityCDPRepayDebtPermission
CommunityCDPRepayDebtPermission allows submission of CommunityCDPRepayDebtProposal






<a name="zgc.committee.v1beta1.CommunityCDPWithdrawCollateralPermission"></a>

### CommunityCDPWithdrawCollateralPermission
CommunityCDPWithdrawCollateralPermission allows submission of CommunityCDPWithdrawCollateralProposal






<a name="zgc.committee.v1beta1.CommunityPoolLendWithdrawPermission"></a>

### CommunityPoolLendWithdrawPermission
CommunityPoolLendWithdrawPermission allows submission of CommunityPoolLendWithdrawProposal






<a name="zgc.committee.v1beta1.GodPermission"></a>

### GodPermission
GodPermission allows any governance proposal. It is used mainly for testing.






<a name="zgc.committee.v1beta1.ParamsChangePermission"></a>

### ParamsChangePermission
ParamsChangePermission allows any parameter or sub parameter change proposal.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `allowed_params_changes` | [AllowedParamsChange](#zgc.committee.v1beta1.AllowedParamsChange) | repeated |  |






<a name="zgc.committee.v1beta1.SoftwareUpgradePermission"></a>

### SoftwareUpgradePermission
SoftwareUpgradePermission permission type for software upgrade proposals






<a name="zgc.committee.v1beta1.SubparamRequirement"></a>

### SubparamRequirement
SubparamRequirement contains requirements for a single record in a subparam value list


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `key` | [string](#string) |  | The required attr key of the param record. |
| `val` | [string](#string) |  | The required param value for the param record key. The key and value is used to match to the target param record. |
| `allowed_subparam_attr_changes` | [string](#string) | repeated | The sub param attrs that are allowed to be changed. |






<a name="zgc.committee.v1beta1.TextPermission"></a>

### TextPermission
TextPermission allows any text governance proposal.





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/committee/v1beta1/proposal.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/committee/v1beta1/proposal.proto



<a name="zgc.committee.v1beta1.CommitteeChangeProposal"></a>

### CommitteeChangeProposal
CommitteeChangeProposal is a gov proposal for creating a new committee or modifying an existing one.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `title` | [string](#string) |  |  |
| `description` | [string](#string) |  |  |
| `new_committee` | [google.protobuf.Any](#google.protobuf.Any) |  |  |






<a name="zgc.committee.v1beta1.CommitteeDeleteProposal"></a>

### CommitteeDeleteProposal
CommitteeDeleteProposal is a gov proposal for removing a committee.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `title` | [string](#string) |  |  |
| `description` | [string](#string) |  |  |
| `committee_id` | [uint64](#uint64) |  |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/committee/v1beta1/query.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/committee/v1beta1/query.proto



<a name="zgc.committee.v1beta1.QueryCommitteeRequest"></a>

### QueryCommitteeRequest
QueryCommitteeRequest defines the request type for querying x/committee committee.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `committee_id` | [uint64](#uint64) |  |  |






<a name="zgc.committee.v1beta1.QueryCommitteeResponse"></a>

### QueryCommitteeResponse
QueryCommitteeResponse defines the response type for querying x/committee committee.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `committee` | [google.protobuf.Any](#google.protobuf.Any) |  |  |






<a name="zgc.committee.v1beta1.QueryCommitteesRequest"></a>

### QueryCommitteesRequest
QueryCommitteesRequest defines the request type for querying x/committee committees.






<a name="zgc.committee.v1beta1.QueryCommitteesResponse"></a>

### QueryCommitteesResponse
QueryCommitteesResponse defines the response type for querying x/committee committees.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `committees` | [google.protobuf.Any](#google.protobuf.Any) | repeated |  |






<a name="zgc.committee.v1beta1.QueryNextProposalIDRequest"></a>

### QueryNextProposalIDRequest
QueryNextProposalIDRequest defines the request type for querying x/committee NextProposalID.






<a name="zgc.committee.v1beta1.QueryNextProposalIDResponse"></a>

### QueryNextProposalIDResponse
QueryNextProposalIDRequest defines the response type for querying x/committee NextProposalID.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `next_proposal_id` | [uint64](#uint64) |  |  |






<a name="zgc.committee.v1beta1.QueryProposalRequest"></a>

### QueryProposalRequest
QueryProposalRequest defines the request type for querying x/committee proposal.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `proposal_id` | [uint64](#uint64) |  |  |






<a name="zgc.committee.v1beta1.QueryProposalResponse"></a>

### QueryProposalResponse
QueryProposalResponse defines the response type for querying x/committee proposal.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `pub_proposal` | [google.protobuf.Any](#google.protobuf.Any) |  |  |
| `id` | [uint64](#uint64) |  |  |
| `committee_id` | [uint64](#uint64) |  |  |
| `deadline` | [google.protobuf.Timestamp](#google.protobuf.Timestamp) |  |  |






<a name="zgc.committee.v1beta1.QueryProposalsRequest"></a>

### QueryProposalsRequest
QueryProposalsRequest defines the request type for querying x/committee proposals.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `committee_id` | [uint64](#uint64) |  |  |






<a name="zgc.committee.v1beta1.QueryProposalsResponse"></a>

### QueryProposalsResponse
QueryProposalsResponse defines the response type for querying x/committee proposals.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `proposals` | [QueryProposalResponse](#zgc.committee.v1beta1.QueryProposalResponse) | repeated |  |






<a name="zgc.committee.v1beta1.QueryRawParamsRequest"></a>

### QueryRawParamsRequest
QueryRawParamsRequest defines the request type for querying x/committee raw params.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `subspace` | [string](#string) |  |  |
| `key` | [string](#string) |  |  |






<a name="zgc.committee.v1beta1.QueryRawParamsResponse"></a>

### QueryRawParamsResponse
QueryRawParamsResponse defines the response type for querying x/committee raw params.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `raw_data` | [string](#string) |  |  |






<a name="zgc.committee.v1beta1.QueryTallyRequest"></a>

### QueryTallyRequest
QueryTallyRequest defines the request type for querying x/committee tally.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `proposal_id` | [uint64](#uint64) |  |  |






<a name="zgc.committee.v1beta1.QueryTallyResponse"></a>

### QueryTallyResponse
QueryTallyResponse defines the response type for querying x/committee tally.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `proposal_id` | [uint64](#uint64) |  |  |
| `yes_votes` | [string](#string) |  |  |
| `no_votes` | [string](#string) |  |  |
| `current_votes` | [string](#string) |  |  |
| `possible_votes` | [string](#string) |  |  |
| `vote_threshold` | [string](#string) |  |  |
| `quorum` | [string](#string) |  |  |






<a name="zgc.committee.v1beta1.QueryVoteRequest"></a>

### QueryVoteRequest
QueryVoteRequest defines the request type for querying x/committee vote.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `proposal_id` | [uint64](#uint64) |  |  |
| `voter` | [string](#string) |  |  |






<a name="zgc.committee.v1beta1.QueryVoteResponse"></a>

### QueryVoteResponse
QueryVoteResponse defines the response type for querying x/committee vote.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `proposal_id` | [uint64](#uint64) |  |  |
| `voter` | [string](#string) |  |  |
| `vote_type` | [VoteType](#zgc.committee.v1beta1.VoteType) |  |  |






<a name="zgc.committee.v1beta1.QueryVotesRequest"></a>

### QueryVotesRequest
QueryVotesRequest defines the request type for querying x/committee votes.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `proposal_id` | [uint64](#uint64) |  |  |
| `pagination` | [cosmos.base.query.v1beta1.PageRequest](#cosmos.base.query.v1beta1.PageRequest) |  |  |






<a name="zgc.committee.v1beta1.QueryVotesResponse"></a>

### QueryVotesResponse
QueryVotesResponse defines the response type for querying x/committee votes.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `votes` | [QueryVoteResponse](#zgc.committee.v1beta1.QueryVoteResponse) | repeated | votes defined the queried votes. |
| `pagination` | [cosmos.base.query.v1beta1.PageResponse](#cosmos.base.query.v1beta1.PageResponse) |  | pagination defines the pagination in the response. |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.committee.v1beta1.Query"></a>

### Query
Query defines the gRPC querier service for committee module

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `Committees` | [QueryCommitteesRequest](#zgc.committee.v1beta1.QueryCommitteesRequest) | [QueryCommitteesResponse](#zgc.committee.v1beta1.QueryCommitteesResponse) | Committees queries all committess of the committee module. | GET|/0g/committee/v1beta1/committees|
| `Committee` | [QueryCommitteeRequest](#zgc.committee.v1beta1.QueryCommitteeRequest) | [QueryCommitteeResponse](#zgc.committee.v1beta1.QueryCommitteeResponse) | Committee queries a committee based on committee ID. | GET|/0g/committee/v1beta1/committees/{committee_id}|
| `Proposals` | [QueryProposalsRequest](#zgc.committee.v1beta1.QueryProposalsRequest) | [QueryProposalsResponse](#zgc.committee.v1beta1.QueryProposalsResponse) | Proposals queries proposals based on committee ID. | GET|/0g/committee/v1beta1/proposals|
| `Proposal` | [QueryProposalRequest](#zgc.committee.v1beta1.QueryProposalRequest) | [QueryProposalResponse](#zgc.committee.v1beta1.QueryProposalResponse) | Deposits queries a proposal based on proposal ID. | GET|/0g/committee/v1beta1/proposals/{proposal_id}|
| `NextProposalID` | [QueryNextProposalIDRequest](#zgc.committee.v1beta1.QueryNextProposalIDRequest) | [QueryNextProposalIDResponse](#zgc.committee.v1beta1.QueryNextProposalIDResponse) | NextProposalID queries the next proposal ID of the committee module. | GET|/0g/committee/v1beta1/next-proposal-id|
| `Votes` | [QueryVotesRequest](#zgc.committee.v1beta1.QueryVotesRequest) | [QueryVotesResponse](#zgc.committee.v1beta1.QueryVotesResponse) | Votes queries all votes for a single proposal ID. | GET|/0g/committee/v1beta1/proposals/{proposal_id}/votes|
| `Vote` | [QueryVoteRequest](#zgc.committee.v1beta1.QueryVoteRequest) | [QueryVoteResponse](#zgc.committee.v1beta1.QueryVoteResponse) | Vote queries the vote of a single voter for a single proposal ID. | GET|/0g/committee/v1beta1/proposals/{proposal_id}/votes/{voter}|
| `Tally` | [QueryTallyRequest](#zgc.committee.v1beta1.QueryTallyRequest) | [QueryTallyResponse](#zgc.committee.v1beta1.QueryTallyResponse) | Tally queries the tally of a single proposal ID. | GET|/0g/committee/v1beta1/proposals/{proposal_id}/tally|
| `RawParams` | [QueryRawParamsRequest](#zgc.committee.v1beta1.QueryRawParamsRequest) | [QueryRawParamsResponse](#zgc.committee.v1beta1.QueryRawParamsResponse) | RawParams queries the raw params data of any subspace and key. | GET|/0g/committee/v1beta1/raw-params|

 <!-- end services -->



<a name="zgc/committee/v1beta1/tx.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/committee/v1beta1/tx.proto



<a name="zgc.committee.v1beta1.MsgSubmitProposal"></a>

### MsgSubmitProposal
MsgSubmitProposal is used by committee members to create a new proposal that they can vote on.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `pub_proposal` | [google.protobuf.Any](#google.protobuf.Any) |  |  |
| `proposer` | [string](#string) |  |  |
| `committee_id` | [uint64](#uint64) |  |  |






<a name="zgc.committee.v1beta1.MsgSubmitProposalResponse"></a>

### MsgSubmitProposalResponse
MsgSubmitProposalResponse defines the SubmitProposal response type


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `proposal_id` | [uint64](#uint64) |  |  |






<a name="zgc.committee.v1beta1.MsgVote"></a>

### MsgVote
MsgVote is submitted by committee members to vote on proposals.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `proposal_id` | [uint64](#uint64) |  |  |
| `voter` | [string](#string) |  |  |
| `vote_type` | [VoteType](#zgc.committee.v1beta1.VoteType) |  |  |






<a name="zgc.committee.v1beta1.MsgVoteResponse"></a>

### MsgVoteResponse
MsgVoteResponse defines the Vote response type





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.committee.v1beta1.Msg"></a>

### Msg
Msg defines the committee Msg service

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `SubmitProposal` | [MsgSubmitProposal](#zgc.committee.v1beta1.MsgSubmitProposal) | [MsgSubmitProposalResponse](#zgc.committee.v1beta1.MsgSubmitProposalResponse) | SubmitProposal defines a method for submitting a committee proposal | |
| `Vote` | [MsgVote](#zgc.committee.v1beta1.MsgVote) | [MsgVoteResponse](#zgc.committee.v1beta1.MsgVoteResponse) | Vote defines a method for voting on a proposal | |

 <!-- end services -->



<a name="zgc/council/v1/genesis.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/council/v1/genesis.proto



<a name="zgc.council.v1.Ballot"></a>

### Ballot



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `id` | [uint64](#uint64) |  |  |
| `content` | [bytes](#bytes) |  |  |






<a name="zgc.council.v1.Council"></a>

### Council



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `id` | [uint64](#uint64) |  |  |
| `voting_start_height` | [uint64](#uint64) |  |  |
| `start_height` | [uint64](#uint64) |  |  |
| `end_height` | [uint64](#uint64) |  |  |
| `votes` | [Vote](#zgc.council.v1.Vote) | repeated |  |
| `members` | [bytes](#bytes) | repeated |  |






<a name="zgc.council.v1.GenesisState"></a>

### GenesisState
GenesisState defines the council module's genesis state.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#kava.community.v1beta1.Params) |  | params defines all the parameters related to commmunity |
| `staking_rewards_state` | [StakingRewardsState](#kava.community.v1beta1.StakingRewardsState) |  | StakingRewardsState stores the internal staking reward data required to track staking rewards across blocks |






<a name="zgc.council.v1.Params"></a>

### Params



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `council_size` | [uint64](#uint64) |  |  |






<a name="zgc.council.v1.Vote"></a>

### Vote



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `council_id` | [uint64](#uint64) |  |  |
| `voter` | [bytes](#bytes) |  |  |
| `ballots` | [Ballot](#zgc.council.v1.Ballot) | repeated |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/council/v1/query.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/council/v1/query.proto



<a name="zgc.council.v1.QueryCurrentCouncilIDRequest"></a>

### QueryCurrentCouncilIDRequest







<a name="zgc.council.v1.QueryCurrentCouncilIDResponse"></a>

### QueryCurrentCouncilIDResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#kava.earn.v1beta1.Params) |  | params defines all the parameters related to earn |
| `vault_records` | [VaultRecord](#kava.earn.v1beta1.VaultRecord) | repeated | vault_records defines the available vaults |
| `vault_share_records` | [VaultShareRecord](#kava.earn.v1beta1.VaultShareRecord) | repeated | share_records defines the owned shares of each vault |






<a name="zgc.council.v1.QueryRegisteredVotersRequest"></a>

### QueryRegisteredVotersRequest







<a name="zgc.council.v1.QueryRegisteredVotersResponse"></a>

### QueryRegisteredVotersResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `voters` | [string](#string) | repeated |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.council.v1.Query"></a>

### Query
Query defines the gRPC querier service for council module

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `CurrentCouncilID` | [QueryCurrentCouncilIDRequest](#zgc.council.v1.QueryCurrentCouncilIDRequest) | [QueryCurrentCouncilIDResponse](#zgc.council.v1.QueryCurrentCouncilIDResponse) |  | GET|/0gchain/council/v1/current-council-id|
| `RegisteredVoters` | [QueryRegisteredVotersRequest](#zgc.council.v1.QueryRegisteredVotersRequest) | [QueryRegisteredVotersResponse](#zgc.council.v1.QueryRegisteredVotersResponse) |  | GET|/0gchain/council/v1/registered-voters|

 <!-- end services -->



<a name="zgc/council/v1/tx.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/council/v1/tx.proto



<a name="zgc.council.v1.MsgRegister"></a>

### MsgRegister



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `voter` | [string](#string) |  |  |
| `key` | [bytes](#bytes) |  |  |






<a name="zgc.council.v1.MsgRegisterResponse"></a>

### MsgRegisterResponse







<a name="zgc.council.v1.MsgVote"></a>

### MsgVote



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `council_id` | [uint64](#uint64) |  |  |
| `voter` | [string](#string) |  |  |
| `ballots` | [Ballot](#zgc.council.v1.Ballot) | repeated |  |






<a name="zgc.council.v1.MsgVoteResponse"></a>

### MsgVoteResponse






 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.council.v1.Msg"></a>

### Msg
Msg defines the council Msg service

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `Register` | [MsgRegister](#zgc.council.v1.MsgRegister) | [MsgRegisterResponse](#zgc.council.v1.MsgRegisterResponse) |  | |
| `Vote` | [MsgVote](#zgc.council.v1.MsgVote) | [MsgVoteResponse](#zgc.council.v1.MsgVoteResponse) |  | |

 <!-- end services -->



<a name="zgc/dasigners/v1/dasigners.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/dasigners/v1/dasigners.proto



<a name="zgc.dasigners.v1.Quorum"></a>

### Quorum



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `signers` | [string](#string) | repeated |  |






<a name="zgc.dasigners.v1.Quorums"></a>

### Quorums



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `quorums` | [Quorum](#zgc.dasigners.v1.Quorum) | repeated |  |






<a name="zgc.dasigners.v1.Signer"></a>

### Signer



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `account` | [string](#string) |  | account defines the hex address of signer without 0x |
| `socket` | [string](#string) |  | socket defines the da node socket address |
| `pubkey_g1` | [bytes](#bytes) |  | pubkey_g1 defines the public key on bn254 G1 |
| `pubkey_g2` | [bytes](#bytes) |  | pubkey_g1 defines the public key on bn254 G2 |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/dasigners/v1/genesis.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/dasigners/v1/genesis.proto



<a name="zgc.dasigners.v1.GenesisState"></a>

### GenesisState
GenesisState defines the dasigners module's genesis state.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#zgc.dasigners.v1.Params) |  | params defines all the parameters of related to deposit. |
| `epoch_number` | [uint64](#uint64) |  | params epoch_number the epoch number |
| `signers` | [Signer](#zgc.dasigners.v1.Signer) | repeated | signers defines all signers information |
| `quorums_by_epoch` | [Quorums](#zgc.dasigners.v1.Quorums) | repeated | quorums_by_epoch defines chosen quorums by epoch |






<a name="zgc.dasigners.v1.Params"></a>

### Params



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `tokens_per_vote` | [uint64](#uint64) |  |  |
| `max_votes_per_signer` | [uint64](#uint64) |  |  |
| `max_quorums` | [uint64](#uint64) |  |  |
| `epoch_blocks` | [uint64](#uint64) |  |  |
| `encoded_slices` | [uint64](#uint64) |  |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/dasigners/v1/query.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/dasigners/v1/query.proto



<a name="zgc.dasigners.v1.QueryAggregatePubkeyG1Request"></a>

### QueryAggregatePubkeyG1Request



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `epoch_number` | [uint64](#uint64) |  |  |
| `quorum_id` | [uint64](#uint64) |  |  |
| `quorum_bitmap` | [bytes](#bytes) |  |  |






<a name="zgc.dasigners.v1.QueryAggregatePubkeyG1Response"></a>

### QueryAggregatePubkeyG1Response



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `aggregate_pubkey_g1` | [bytes](#bytes) |  |  |
| `total` | [uint64](#uint64) |  |  |
| `hit` | [uint64](#uint64) |  |  |






<a name="zgc.dasigners.v1.QueryEpochNumberRequest"></a>

### QueryEpochNumberRequest







<a name="zgc.dasigners.v1.QueryEpochNumberResponse"></a>

### QueryEpochNumberResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `epoch_number` | [uint64](#uint64) |  |  |






<a name="zgc.dasigners.v1.QueryEpochQuorumRequest"></a>

### QueryEpochQuorumRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `epoch_number` | [uint64](#uint64) |  |  |
| `quorum_id` | [uint64](#uint64) |  |  |






<a name="zgc.dasigners.v1.QueryEpochQuorumResponse"></a>

### QueryEpochQuorumResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `quorum` | [Quorum](#zgc.dasigners.v1.Quorum) |  |  |






<a name="zgc.dasigners.v1.QueryEpochQuorumRowRequest"></a>

### QueryEpochQuorumRowRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `epoch_number` | [uint64](#uint64) |  |  |
| `quorum_id` | [uint64](#uint64) |  |  |
| `row_index` | [uint32](#uint32) |  |  |






<a name="zgc.dasigners.v1.QueryEpochQuorumRowResponse"></a>

### QueryEpochQuorumRowResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `signer` | [string](#string) |  |  |






<a name="zgc.dasigners.v1.QueryQuorumCountRequest"></a>

### QueryQuorumCountRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `epoch_number` | [uint64](#uint64) |  |  |






<a name="zgc.dasigners.v1.QueryQuorumCountResponse"></a>

### QueryQuorumCountResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `quorum_count` | [uint64](#uint64) |  |  |






<a name="zgc.dasigners.v1.QuerySignerRequest"></a>

### QuerySignerRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `accounts` | [string](#string) | repeated |  |






<a name="zgc.dasigners.v1.QuerySignerResponse"></a>

### QuerySignerResponse



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `signer` | [Signer](#zgc.dasigners.v1.Signer) | repeated |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.dasigners.v1.Query"></a>

### Query
Query defines the gRPC querier service for the dasigners module

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `EpochNumber` | [QueryEpochNumberRequest](#zgc.dasigners.v1.QueryEpochNumberRequest) | [QueryEpochNumberResponse](#zgc.dasigners.v1.QueryEpochNumberResponse) |  | GET|/0g/dasigners/v1/epoch-number|
| `QuorumCount` | [QueryQuorumCountRequest](#zgc.dasigners.v1.QueryQuorumCountRequest) | [QueryQuorumCountResponse](#zgc.dasigners.v1.QueryQuorumCountResponse) |  | GET|/0g/dasigners/v1/quorum-count|
| `EpochQuorum` | [QueryEpochQuorumRequest](#zgc.dasigners.v1.QueryEpochQuorumRequest) | [QueryEpochQuorumResponse](#zgc.dasigners.v1.QueryEpochQuorumResponse) |  | GET|/0g/dasigners/v1/epoch-quorum|
| `EpochQuorumRow` | [QueryEpochQuorumRowRequest](#zgc.dasigners.v1.QueryEpochQuorumRowRequest) | [QueryEpochQuorumRowResponse](#zgc.dasigners.v1.QueryEpochQuorumRowResponse) |  | GET|/0g/dasigners/v1/epoch-quorum-row|
| `AggregatePubkeyG1` | [QueryAggregatePubkeyG1Request](#zgc.dasigners.v1.QueryAggregatePubkeyG1Request) | [QueryAggregatePubkeyG1Response](#zgc.dasigners.v1.QueryAggregatePubkeyG1Response) |  | GET|/0g/dasigners/v1/aggregate-pubkey-g1|
| `Signer` | [QuerySignerRequest](#zgc.dasigners.v1.QuerySignerRequest) | [QuerySignerResponse](#zgc.dasigners.v1.QuerySignerResponse) |  | GET|/0g/dasigners/v1/signer|

 <!-- end services -->



<a name="zgc/dasigners/v1/tx.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/dasigners/v1/tx.proto



<a name="zgc.dasigners.v1.MsgRegisterNextEpoch"></a>

### MsgRegisterNextEpoch



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `account` | [string](#string) |  |  |
| `signature` | [bytes](#bytes) |  |  |






<a name="zgc.dasigners.v1.MsgRegisterNextEpochResponse"></a>

### MsgRegisterNextEpochResponse







<a name="zgc.dasigners.v1.MsgRegisterSigner"></a>

### MsgRegisterSigner



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `signer` | [Signer](#zgc.dasigners.v1.Signer) |  |  |
| `signature` | [bytes](#bytes) |  |  |






<a name="zgc.dasigners.v1.MsgRegisterSignerResponse"></a>

### MsgRegisterSignerResponse







<a name="zgc.dasigners.v1.MsgUpdateSocket"></a>

### MsgUpdateSocket



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `account` | [string](#string) |  |  |
| `socket` | [string](#string) |  |  |






<a name="zgc.dasigners.v1.MsgUpdateSocketResponse"></a>

### MsgUpdateSocketResponse






 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.dasigners.v1.Msg"></a>

### Msg
Msg defines the dasigners Msg service

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `RegisterSigner` | [MsgRegisterSigner](#zgc.dasigners.v1.MsgRegisterSigner) | [MsgRegisterSignerResponse](#zgc.dasigners.v1.MsgRegisterSignerResponse) |  | |
| `UpdateSocket` | [MsgUpdateSocket](#zgc.dasigners.v1.MsgUpdateSocket) | [MsgUpdateSocketResponse](#zgc.dasigners.v1.MsgUpdateSocketResponse) |  | |
| `RegisterNextEpoch` | [MsgRegisterNextEpoch](#zgc.dasigners.v1.MsgRegisterNextEpoch) | [MsgRegisterNextEpochResponse](#zgc.dasigners.v1.MsgRegisterNextEpochResponse) |  | |

 <!-- end services -->



<a name="zgc/evmutil/v1beta1/conversion_pair.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/evmutil/v1beta1/conversion_pair.proto



<a name="zgc.evmutil.v1beta1.AllowedCosmosCoinERC20Token"></a>

### AllowedCosmosCoinERC20Token
AllowedCosmosCoinERC20Token defines allowed cosmos-sdk denom & metadata
for evm token representations of sdk assets.
NOTE: once evm token contracts are deployed, changes to metadata for a given
cosmos_denom will not change metadata of deployed contract.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `cosmos_denom` | [string](#string) |  | Denom of the sdk.Coin |
| `name` | [string](#string) |  | Name of ERC20 contract |
| `symbol` | [string](#string) |  | Symbol of ERC20 contract |
| `decimals` | [uint32](#uint32) |  | Number of decimals ERC20 contract is deployed with. |






<a name="zgc.evmutil.v1beta1.ConversionPair"></a>

### ConversionPair
ConversionPair defines a 0gChain ERC20 address and corresponding denom that is
allowed to be converted between ERC20 and sdk.Coin


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `zgchain_erc20_address` | [bytes](#bytes) |  | ERC20 address of the token on the 0gChain EVM |
| `denom` | [string](#string) |  | Denom of the corresponding sdk.Coin |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/evmutil/v1beta1/genesis.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/evmutil/v1beta1/genesis.proto



<a name="zgc.evmutil.v1beta1.Account"></a>

### Account
BalanceAccount defines an account in the evmutil module.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `address` | [bytes](#bytes) |  |  |
| `balance` | [string](#string) |  | balance indicates the amount of neuron owned by the address. |






<a name="zgc.evmutil.v1beta1.GenesisState"></a>

### GenesisState
GenesisState defines the evmutil module's genesis state.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `accounts` | [Account](#zgc.evmutil.v1beta1.Account) | repeated |  |
| `params` | [Params](#zgc.evmutil.v1beta1.Params) |  | params defines all the parameters of the module. |






<a name="zgc.evmutil.v1beta1.Params"></a>

### Params
Params defines the evmutil module params


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `enabled_conversion_pairs` | [ConversionPair](#zgc.evmutil.v1beta1.ConversionPair) | repeated | enabled_conversion_pairs defines the list of conversion pairs allowed to be converted between 0gChain ERC20 and sdk.Coin |
| `allowed_cosmos_denoms` | [AllowedCosmosCoinERC20Token](#zgc.evmutil.v1beta1.AllowedCosmosCoinERC20Token) | repeated | allowed_cosmos_denoms is a list of denom & erc20 token metadata pairs. if a denom is in the list, it is allowed to be converted to an erc20 in the evm. |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/evmutil/v1beta1/query.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/evmutil/v1beta1/query.proto



<a name="zgc.evmutil.v1beta1.DeployedCosmosCoinContract"></a>

### DeployedCosmosCoinContract
DeployedCosmosCoinContract defines a deployed token contract to the evm representing a native cosmos-sdk coin


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `cosmos_denom` | [string](#string) |  |  |
| `address` | [string](#string) |  |  |






<a name="zgc.evmutil.v1beta1.QueryDeployedCosmosCoinContractsRequest"></a>

### QueryDeployedCosmosCoinContractsRequest
QueryDeployedCosmosCoinContractsRequest defines the request type for Query/DeployedCosmosCoinContracts method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `cosmos_denoms` | [string](#string) | repeated | optional query param to only return specific denoms in the list denoms that do not have deployed contracts will be omitted from the result must request fewer than 100 denoms at a time. |
| `pagination` | [cosmos.base.query.v1beta1.PageRequest](#cosmos.base.query.v1beta1.PageRequest) |  | pagination defines an optional pagination for the request. |






<a name="zgc.evmutil.v1beta1.QueryDeployedCosmosCoinContractsResponse"></a>

### QueryDeployedCosmosCoinContractsResponse
QueryDeployedCosmosCoinContractsResponse defines the response type for the Query/DeployedCosmosCoinContracts method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `deployed_cosmos_coin_contracts` | [DeployedCosmosCoinContract](#zgc.evmutil.v1beta1.DeployedCosmosCoinContract) | repeated | deployed_cosmos_coin_contracts is a list of cosmos-sdk coin denom and its deployed contract address |
| `pagination` | [cosmos.base.query.v1beta1.PageResponse](#cosmos.base.query.v1beta1.PageResponse) |  | pagination defines the pagination in the response. |






<a name="zgc.evmutil.v1beta1.QueryParamsRequest"></a>

### QueryParamsRequest
QueryParamsRequest defines the request type for querying x/evmutil parameters.






<a name="zgc.evmutil.v1beta1.QueryParamsResponse"></a>

### QueryParamsResponse
QueryParamsResponse defines the response type for querying x/evmutil parameters.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#zgc.evmutil.v1beta1.Params) |  |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.evmutil.v1beta1.Query"></a>

### Query
Query defines the gRPC querier service for evmutil module

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `Params` | [QueryParamsRequest](#zgc.evmutil.v1beta1.QueryParamsRequest) | [QueryParamsResponse](#zgc.evmutil.v1beta1.QueryParamsResponse) | Params queries all parameters of the evmutil module. | GET|/0g/evmutil/v1beta1/params|
| `DeployedCosmosCoinContracts` | [QueryDeployedCosmosCoinContractsRequest](#zgc.evmutil.v1beta1.QueryDeployedCosmosCoinContractsRequest) | [QueryDeployedCosmosCoinContractsResponse](#zgc.evmutil.v1beta1.QueryDeployedCosmosCoinContractsResponse) | DeployedCosmosCoinContracts queries a list cosmos coin denom and their deployed erc20 address | GET|/0g/evmutil/v1beta1/deployed_cosmos_coin_contracts|

 <!-- end services -->



<a name="zgc/evmutil/v1beta1/tx.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/evmutil/v1beta1/tx.proto



<a name="zgc.evmutil.v1beta1.MsgConvertCoinToERC20"></a>

### MsgConvertCoinToERC20
MsgConvertCoinToERC20 defines a conversion from sdk.Coin to 0gChain ERC20 for EVM-native assets.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `initiator` | [string](#string) |  | 0gChain bech32 address initiating the conversion. |
| `receiver` | [string](#string) |  | EVM 0x hex address that will receive the converted 0gChain ERC20 tokens. |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | Amount is the sdk.Coin amount to convert. |






<a name="zgc.evmutil.v1beta1.MsgConvertCoinToERC20Response"></a>

### MsgConvertCoinToERC20Response
MsgConvertCoinToERC20Response defines the response value from Msg/ConvertCoinToERC20.






<a name="zgc.evmutil.v1beta1.MsgConvertCosmosCoinFromERC20"></a>

### MsgConvertCosmosCoinFromERC20
MsgConvertCosmosCoinFromERC20 defines a conversion from ERC20 to cosmos coins for cosmos-native assets.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `initiator` | [string](#string) |  | EVM hex address initiating the conversion. |
| `receiver` | [string](#string) |  | 0gChain bech32 address that will receive the cosmos coins. |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | Amount is the amount to convert, expressed as a Cosmos coin. |






<a name="zgc.evmutil.v1beta1.MsgConvertCosmosCoinFromERC20Response"></a>

### MsgConvertCosmosCoinFromERC20Response
MsgConvertCosmosCoinFromERC20Response defines the response value from Msg/MsgConvertCosmosCoinFromERC20.






<a name="zgc.evmutil.v1beta1.MsgConvertCosmosCoinToERC20"></a>

### MsgConvertCosmosCoinToERC20
MsgConvertCosmosCoinToERC20 defines a conversion from cosmos sdk.Coin to ERC20 for cosmos-native assets.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `initiator` | [string](#string) |  | 0gChain bech32 address initiating the conversion. |
| `receiver` | [string](#string) |  | EVM hex address that will receive the ERC20 tokens. |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | Amount is the sdk.Coin amount to convert. |






<a name="zgc.evmutil.v1beta1.MsgConvertCosmosCoinToERC20Response"></a>

### MsgConvertCosmosCoinToERC20Response
MsgConvertCosmosCoinToERC20Response defines the response value from Msg/MsgConvertCosmosCoinToERC20.






<a name="zgc.evmutil.v1beta1.MsgConvertERC20ToCoin"></a>

### MsgConvertERC20ToCoin
MsgConvertERC20ToCoin defines a conversion from 0gChain ERC20 to sdk.Coin for EVM-native assets.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `initiator` | [string](#string) |  | EVM 0x hex address initiating the conversion. |
| `receiver` | [string](#string) |  | 0gChain bech32 address that will receive the converted sdk.Coin. |
| `zgchain_erc20_address` | [string](#string) |  | EVM 0x hex address of the ERC20 contract. |
| `amount` | [string](#string) |  | ERC20 token amount to convert. |






<a name="zgc.evmutil.v1beta1.MsgConvertERC20ToCoinResponse"></a>

### MsgConvertERC20ToCoinResponse
MsgConvertERC20ToCoinResponse defines the response value from
Msg/MsgConvertERC20ToCoin.





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.evmutil.v1beta1.Msg"></a>

### Msg
Msg defines the evmutil Msg service.

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `ConvertCoinToERC20` | [MsgConvertCoinToERC20](#zgc.evmutil.v1beta1.MsgConvertCoinToERC20) | [MsgConvertCoinToERC20Response](#zgc.evmutil.v1beta1.MsgConvertCoinToERC20Response) | ConvertCoinToERC20 defines a method for converting sdk.Coin to 0gChain ERC20. | |
| `ConvertERC20ToCoin` | [MsgConvertERC20ToCoin](#zgc.evmutil.v1beta1.MsgConvertERC20ToCoin) | [MsgConvertERC20ToCoinResponse](#zgc.evmutil.v1beta1.MsgConvertERC20ToCoinResponse) | ConvertERC20ToCoin defines a method for converting 0gChain ERC20 to sdk.Coin. | |
| `ConvertCosmosCoinToERC20` | [MsgConvertCosmosCoinToERC20](#zgc.evmutil.v1beta1.MsgConvertCosmosCoinToERC20) | [MsgConvertCosmosCoinToERC20Response](#zgc.evmutil.v1beta1.MsgConvertCosmosCoinToERC20Response) | ConvertCosmosCoinToERC20 defines a method for converting a cosmos sdk.Coin to an ERC20. | |
| `ConvertCosmosCoinFromERC20` | [MsgConvertCosmosCoinFromERC20](#zgc.evmutil.v1beta1.MsgConvertCosmosCoinFromERC20) | [MsgConvertCosmosCoinFromERC20Response](#zgc.evmutil.v1beta1.MsgConvertCosmosCoinFromERC20Response) | ConvertCosmosCoinFromERC20 defines a method for converting a cosmos sdk.Coin to an ERC20. | |

 <!-- end services -->



<a name="zgc/issuance/v1beta1/genesis.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/issuance/v1beta1/genesis.proto



<a name="zgc.issuance.v1beta1.Asset"></a>

### Asset
Asset type for assets in the issuance module


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `owner` | [string](#string) |  |  |
| `denom` | [string](#string) |  |  |
| `blocked_addresses` | [string](#string) | repeated |  |
| `paused` | [bool](#bool) |  |  |
| `blockable` | [bool](#bool) |  |  |
| `rate_limit` | [RateLimit](#zgc.issuance.v1beta1.RateLimit) |  |  |






<a name="zgc.issuance.v1beta1.AssetSupply"></a>

### AssetSupply
AssetSupply contains information about an asset's rate-limited supply (the
total supply of the asset is tracked in the top-level supply module)


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `current_supply` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `time_elapsed` | [google.protobuf.Duration](#google.protobuf.Duration) |  |  |






<a name="zgc.issuance.v1beta1.GenesisState"></a>

### GenesisState
GenesisState defines the issuance module's genesis state.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#kava.issuance.v1beta1.Params) |  | params defines all the parameters of the module. |
| `supplies` | [AssetSupply](#kava.issuance.v1beta1.AssetSupply) | repeated |  |






<a name="zgc.issuance.v1beta1.Params"></a>

### Params
Params defines the parameters for the issuance module.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `assets` | [Asset](#zgc.issuance.v1beta1.Asset) | repeated |  |






<a name="zgc.issuance.v1beta1.RateLimit"></a>

### RateLimit
RateLimit parameters for rate-limiting the supply of an issued asset


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `active` | [bool](#bool) |  |  |
| `limit` | [bytes](#bytes) |  |  |
| `time_period` | [google.protobuf.Duration](#google.protobuf.Duration) |  |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/issuance/v1beta1/query.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/issuance/v1beta1/query.proto



<a name="zgc.issuance.v1beta1.QueryParamsRequest"></a>

### QueryParamsRequest
QueryParamsRequest defines the request type for querying x/issuance parameters.






<a name="zgc.issuance.v1beta1.QueryParamsResponse"></a>

### QueryParamsResponse
QueryParamsResponse defines the response type for querying x/issuance parameters.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#zgc.issuance.v1beta1.Params) |  |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.issuance.v1beta1.Query"></a>

### Query
Query defines the gRPC querier service for issuance module

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `Params` | [QueryParamsRequest](#zgc.issuance.v1beta1.QueryParamsRequest) | [QueryParamsResponse](#zgc.issuance.v1beta1.QueryParamsResponse) | Params queries all parameters of the issuance module. | GET|/0g/issuance/v1beta1/params|

 <!-- end services -->



<a name="zgc/issuance/v1beta1/tx.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/issuance/v1beta1/tx.proto



<a name="zgc.issuance.v1beta1.MsgBlockAddress"></a>

### MsgBlockAddress
MsgBlockAddress represents a message used by the issuer to block an address from holding or transferring tokens


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `sender` | [string](#string) |  |  |
| `denom` | [string](#string) |  |  |
| `blocked_address` | [string](#string) |  |  |






<a name="zgc.issuance.v1beta1.MsgBlockAddressResponse"></a>

### MsgBlockAddressResponse
MsgBlockAddressResponse defines the Msg/BlockAddress response type.






<a name="zgc.issuance.v1beta1.MsgIssueTokens"></a>

### MsgIssueTokens
MsgIssueTokens represents a message used by the issuer to issue new tokens


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `sender` | [string](#string) |  |  |
| `tokens` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |
| `receiver` | [string](#string) |  |  |






<a name="zgc.issuance.v1beta1.MsgIssueTokensResponse"></a>

### MsgIssueTokensResponse
MsgIssueTokensResponse defines the Msg/IssueTokens response type.






<a name="zgc.issuance.v1beta1.MsgRedeemTokens"></a>

### MsgRedeemTokens
MsgRedeemTokens represents a message used by the issuer to redeem (burn) tokens


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `sender` | [string](#string) |  |  |
| `tokens` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  |  |






<a name="zgc.issuance.v1beta1.MsgRedeemTokensResponse"></a>

### MsgRedeemTokensResponse
MsgRedeemTokensResponse defines the Msg/RedeemTokens response type.






<a name="zgc.issuance.v1beta1.MsgSetPauseStatus"></a>

### MsgSetPauseStatus
MsgSetPauseStatus message type used by the issuer to pause or unpause status


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `sender` | [string](#string) |  |  |
| `denom` | [string](#string) |  |  |
| `status` | [bool](#bool) |  |  |






<a name="zgc.issuance.v1beta1.MsgSetPauseStatusResponse"></a>

### MsgSetPauseStatusResponse
MsgSetPauseStatusResponse defines the Msg/SetPauseStatus response type.






<a name="zgc.issuance.v1beta1.MsgUnblockAddress"></a>

### MsgUnblockAddress
MsgUnblockAddress message type used by the issuer to unblock an address from holding or transferring tokens


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `sender` | [string](#string) |  |  |
| `denom` | [string](#string) |  |  |
| `blocked_address` | [string](#string) |  |  |






<a name="zgc.issuance.v1beta1.MsgUnblockAddressResponse"></a>

### MsgUnblockAddressResponse
MsgUnblockAddressResponse defines the Msg/UnblockAddress response type.





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.issuance.v1beta1.Msg"></a>

### Msg
Msg defines the issuance Msg service.

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `IssueTokens` | [MsgIssueTokens](#zgc.issuance.v1beta1.MsgIssueTokens) | [MsgIssueTokensResponse](#zgc.issuance.v1beta1.MsgIssueTokensResponse) | IssueTokens message type used by the issuer to issue new tokens | |
| `RedeemTokens` | [MsgRedeemTokens](#zgc.issuance.v1beta1.MsgRedeemTokens) | [MsgRedeemTokensResponse](#zgc.issuance.v1beta1.MsgRedeemTokensResponse) | RedeemTokens message type used by the issuer to redeem (burn) tokens | |
| `BlockAddress` | [MsgBlockAddress](#zgc.issuance.v1beta1.MsgBlockAddress) | [MsgBlockAddressResponse](#zgc.issuance.v1beta1.MsgBlockAddressResponse) | BlockAddress message type used by the issuer to block an address from holding or transferring tokens | |
| `UnblockAddress` | [MsgUnblockAddress](#zgc.issuance.v1beta1.MsgUnblockAddress) | [MsgUnblockAddressResponse](#zgc.issuance.v1beta1.MsgUnblockAddressResponse) | UnblockAddress message type used by the issuer to unblock an address from holding or transferring tokens | |
| `SetPauseStatus` | [MsgSetPauseStatus](#zgc.issuance.v1beta1.MsgSetPauseStatus) | [MsgSetPauseStatusResponse](#zgc.issuance.v1beta1.MsgSetPauseStatusResponse) | SetPauseStatus message type used to pause or unpause status | |

 <!-- end services -->



<a name="zgc/pricefeed/v1beta1/store.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/pricefeed/v1beta1/store.proto



<a name="zgc.pricefeed.v1beta1.CurrentPrice"></a>

### CurrentPrice
CurrentPrice defines a current price for a particular market in the pricefeed
module.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `market_id` | [string](#string) |  |  |
| `price` | [string](#string) |  |  |






<a name="zgc.pricefeed.v1beta1.Market"></a>

### Market
Market defines an asset in the pricefeed.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `market_id` | [string](#string) |  |  |
| `base_asset` | [string](#string) |  |  |
| `quote_asset` | [string](#string) |  |  |
| `oracles` | [bytes](#bytes) | repeated |  |
| `active` | [bool](#bool) |  |  |






<a name="zgc.pricefeed.v1beta1.Params"></a>

### Params
Params defines the parameters for the pricefeed module.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `markets` | [Market](#zgc.pricefeed.v1beta1.Market) | repeated |  |






<a name="zgc.pricefeed.v1beta1.PostedPrice"></a>

### PostedPrice
PostedPrice defines a price for market posted by a specific oracle.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `market_id` | [string](#string) |  |  |
| `oracle_address` | [bytes](#bytes) |  |  |
| `price` | [string](#string) |  |  |
| `expiry` | [google.protobuf.Timestamp](#google.protobuf.Timestamp) |  |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/pricefeed/v1beta1/genesis.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/pricefeed/v1beta1/genesis.proto



<a name="zgc.pricefeed.v1beta1.GenesisState"></a>

### GenesisState
GenesisState defines the pricefeed module's genesis state.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#kava.pricefeed.v1beta1.Params) |  | params defines all the parameters of the module. |
| `posted_prices` | [PostedPrice](#kava.pricefeed.v1beta1.PostedPrice) | repeated |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="zgc/pricefeed/v1beta1/query.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/pricefeed/v1beta1/query.proto



<a name="zgc.pricefeed.v1beta1.CurrentPriceResponse"></a>

### CurrentPriceResponse
CurrentPriceResponse defines a current price for a particular market in the pricefeed
module.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `market_id` | [string](#string) |  |  |
| `price` | [string](#string) |  |  |






<a name="zgc.pricefeed.v1beta1.MarketResponse"></a>

### MarketResponse
MarketResponse defines an asset in the pricefeed.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `market_id` | [string](#string) |  |  |
| `base_asset` | [string](#string) |  |  |
| `quote_asset` | [string](#string) |  |  |
| `oracles` | [string](#string) | repeated |  |
| `active` | [bool](#bool) |  |  |






<a name="zgc.pricefeed.v1beta1.PostedPriceResponse"></a>

### PostedPriceResponse
PostedPriceResponse defines a price for market posted by a specific oracle.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `market_id` | [string](#string) |  |  |
| `oracle_address` | [string](#string) |  |  |
| `price` | [string](#string) |  |  |
| `expiry` | [google.protobuf.Timestamp](#google.protobuf.Timestamp) |  |  |






<a name="zgc.pricefeed.v1beta1.QueryMarketsRequest"></a>

### QueryMarketsRequest
QueryMarketsRequest is the request type for the Query/Markets RPC method.






<a name="zgc.pricefeed.v1beta1.QueryMarketsResponse"></a>

### QueryMarketsResponse
QueryMarketsResponse is the response type for the Query/Markets RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `markets` | [MarketResponse](#zgc.pricefeed.v1beta1.MarketResponse) | repeated | List of markets |






<a name="zgc.pricefeed.v1beta1.QueryOraclesRequest"></a>

### QueryOraclesRequest
QueryOraclesRequest is the request type for the Query/Oracles RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `market_id` | [string](#string) |  |  |






<a name="zgc.pricefeed.v1beta1.QueryOraclesResponse"></a>

### QueryOraclesResponse
QueryOraclesResponse is the response type for the Query/Oracles RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `oracles` | [string](#string) | repeated | List of oracle addresses |






<a name="zgc.pricefeed.v1beta1.QueryParamsRequest"></a>

### QueryParamsRequest
QueryParamsRequest defines the request type for querying x/pricefeed
parameters.






<a name="zgc.pricefeed.v1beta1.QueryParamsResponse"></a>

### QueryParamsResponse
QueryParamsResponse defines the response type for querying x/pricefeed
parameters.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#zgc.pricefeed.v1beta1.Params) |  |  |






<a name="zgc.pricefeed.v1beta1.QueryPriceRequest"></a>

### QueryPriceRequest
QueryPriceRequest is the request type for the Query/PriceRequest RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `market_id` | [string](#string) |  |  |






<a name="zgc.pricefeed.v1beta1.QueryPriceResponse"></a>

### QueryPriceResponse
QueryPriceResponse is the response type for the Query/Prices RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `price` | [CurrentPriceResponse](#zgc.pricefeed.v1beta1.CurrentPriceResponse) |  |  |






<a name="zgc.pricefeed.v1beta1.QueryPricesRequest"></a>

### QueryPricesRequest
QueryPricesRequest is the request type for the Query/Prices RPC method.






<a name="zgc.pricefeed.v1beta1.QueryPricesResponse"></a>

### QueryPricesResponse
QueryPricesResponse is the response type for the Query/Prices RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `prices` | [CurrentPriceResponse](#zgc.pricefeed.v1beta1.CurrentPriceResponse) | repeated |  |






<a name="zgc.pricefeed.v1beta1.QueryRawPricesRequest"></a>

### QueryRawPricesRequest
QueryRawPricesRequest is the request type for the Query/RawPrices RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `market_id` | [string](#string) |  |  |






<a name="zgc.pricefeed.v1beta1.QueryRawPricesResponse"></a>

### QueryRawPricesResponse
QueryRawPricesResponse is the response type for the Query/RawPrices RPC
method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `raw_prices` | [PostedPriceResponse](#zgc.pricefeed.v1beta1.PostedPriceResponse) | repeated |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.pricefeed.v1beta1.Query"></a>

### Query
Query defines the gRPC querier service for pricefeed module

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `Params` | [QueryParamsRequest](#zgc.pricefeed.v1beta1.QueryParamsRequest) | [QueryParamsResponse](#zgc.pricefeed.v1beta1.QueryParamsResponse) | Params queries all parameters of the pricefeed module. | GET|/0g/pricefeed/v1beta1/params|
| `Price` | [QueryPriceRequest](#zgc.pricefeed.v1beta1.QueryPriceRequest) | [QueryPriceResponse](#zgc.pricefeed.v1beta1.QueryPriceResponse) | Price queries price details based on a market | GET|/0g/pricefeed/v1beta1/prices/{market_id}|
| `Prices` | [QueryPricesRequest](#zgc.pricefeed.v1beta1.QueryPricesRequest) | [QueryPricesResponse](#zgc.pricefeed.v1beta1.QueryPricesResponse) | Prices queries all prices | GET|/0g/pricefeed/v1beta1/prices|
| `RawPrices` | [QueryRawPricesRequest](#zgc.pricefeed.v1beta1.QueryRawPricesRequest) | [QueryRawPricesResponse](#zgc.pricefeed.v1beta1.QueryRawPricesResponse) | RawPrices queries all raw prices based on a market | GET|/0g/pricefeed/v1beta1/rawprices/{market_id}|
| `Oracles` | [QueryOraclesRequest](#zgc.pricefeed.v1beta1.QueryOraclesRequest) | [QueryOraclesResponse](#zgc.pricefeed.v1beta1.QueryOraclesResponse) | Oracles queries all oracles based on a market | GET|/0g/pricefeed/v1beta1/oracles/{market_id}|
| `Markets` | [QueryMarketsRequest](#zgc.pricefeed.v1beta1.QueryMarketsRequest) | [QueryMarketsResponse](#zgc.pricefeed.v1beta1.QueryMarketsResponse) | Markets queries all markets | GET|/0g/pricefeed/v1beta1/markets|

 <!-- end services -->



<a name="zgc/pricefeed/v1beta1/tx.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## zgc/pricefeed/v1beta1/tx.proto



<a name="zgc.pricefeed.v1beta1.MsgPostPrice"></a>

### MsgPostPrice
MsgPostPrice represents a method for creating a new post price


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `from` | [string](#string) |  | address of client |
| `market_id` | [string](#string) |  |  |
| `price` | [string](#string) |  |  |
| `expiry` | [google.protobuf.Timestamp](#google.protobuf.Timestamp) |  |  |






<a name="zgc.pricefeed.v1beta1.MsgPostPriceResponse"></a>

### MsgPostPriceResponse
MsgPostPriceResponse defines the Msg/PostPrice response type.





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="zgc.pricefeed.v1beta1.Msg"></a>

### Msg
Msg defines the pricefeed Msg service.

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `PostPrice` | [MsgPostPrice](#kava.pricefeed.v1beta1.MsgPostPrice) | [MsgPostPriceResponse](#kava.pricefeed.v1beta1.MsgPostPriceResponse) | PostPrice defines a method for creating a new post price | |

 <!-- end services -->



<a name="kava/router/v1beta1/tx.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/router/v1beta1/tx.proto



<a name="kava.router.v1beta1.MsgDelegateMintDeposit"></a>

### MsgDelegateMintDeposit
MsgDelegateMintDeposit delegates tokens to a validator, then converts them into staking derivatives,
then deposits to an earn vault.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `depositor` | [string](#string) |  | depositor represents the owner of the tokens to delegate |
| `validator` | [string](#string) |  | validator is the address of the validator to delegate to |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | amount is the tokens to delegate |






<a name="kava.router.v1beta1.MsgDelegateMintDepositResponse"></a>

### MsgDelegateMintDepositResponse
MsgDelegateMintDepositResponse defines the Msg/MsgDelegateMintDeposit response type.






<a name="kava.router.v1beta1.MsgMintDeposit"></a>

### MsgMintDeposit
MsgMintDeposit converts a delegation into staking derivatives and deposits it all into an earn vault.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `depositor` | [string](#string) |  | depositor represents the owner of the delegation to convert |
| `validator` | [string](#string) |  | validator is the validator for the depositor's delegation |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | amount is the delegation balance to convert |






<a name="kava.router.v1beta1.MsgMintDepositResponse"></a>

### MsgMintDepositResponse
MsgMintDepositResponse defines the Msg/MsgMintDeposit response type.






<a name="kava.router.v1beta1.MsgWithdrawBurn"></a>

### MsgWithdrawBurn
MsgWithdrawBurn removes staking derivatives from an earn vault and converts them back to a staking delegation.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `from` | [string](#string) |  | from is the owner of the earn vault to withdraw from |
| `validator` | [string](#string) |  | validator is the address to select the derivative denom to withdraw |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | amount is the staked token equivalent to withdraw |






<a name="kava.router.v1beta1.MsgWithdrawBurnResponse"></a>

### MsgWithdrawBurnResponse
MsgWithdrawBurnResponse defines the Msg/MsgWithdrawBurn response type.






<a name="kava.router.v1beta1.MsgWithdrawBurnUndelegate"></a>

### MsgWithdrawBurnUndelegate
MsgWithdrawBurnUndelegate removes staking derivatives from an earn vault, converts them to a staking delegation,
then undelegates them from their validator.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `from` | [string](#string) |  | from is the owner of the earn vault to withdraw from |
| `validator` | [string](#string) |  | validator is the address to select the derivative denom to withdraw |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | amount is the staked token equivalent to withdraw |






<a name="kava.router.v1beta1.MsgWithdrawBurnUndelegateResponse"></a>

### MsgWithdrawBurnUndelegateResponse
MsgWithdrawBurnUndelegateResponse defines the Msg/MsgWithdrawBurnUndelegate response type.





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="kava.router.v1beta1.Msg"></a>

### Msg
Msg defines the router Msg service.

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `MintDeposit` | [MsgMintDeposit](#kava.router.v1beta1.MsgMintDeposit) | [MsgMintDepositResponse](#kava.router.v1beta1.MsgMintDepositResponse) | MintDeposit converts a delegation into staking derivatives and deposits it all into an earn vault. | |
| `DelegateMintDeposit` | [MsgDelegateMintDeposit](#kava.router.v1beta1.MsgDelegateMintDeposit) | [MsgDelegateMintDepositResponse](#kava.router.v1beta1.MsgDelegateMintDepositResponse) | DelegateMintDeposit delegates tokens to a validator, then converts them into staking derivatives, then deposits to an earn vault. | |
| `WithdrawBurn` | [MsgWithdrawBurn](#kava.router.v1beta1.MsgWithdrawBurn) | [MsgWithdrawBurnResponse](#kava.router.v1beta1.MsgWithdrawBurnResponse) | WithdrawBurn removes staking derivatives from an earn vault and converts them back to a staking delegation. | |
| `WithdrawBurnUndelegate` | [MsgWithdrawBurnUndelegate](#kava.router.v1beta1.MsgWithdrawBurnUndelegate) | [MsgWithdrawBurnUndelegateResponse](#kava.router.v1beta1.MsgWithdrawBurnUndelegateResponse) | WithdrawBurnUndelegate removes staking derivatives from an earn vault, converts them to a staking delegation, then undelegates them from their validator. | |

 <!-- end services -->



<a name="kava/savings/v1beta1/store.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/savings/v1beta1/store.proto



<a name="kava.savings.v1beta1.Deposit"></a>

### Deposit
Deposit defines an amount of coins deposited into a savings module account.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `depositor` | [string](#string) |  |  |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) | repeated |  |






<a name="kava.savings.v1beta1.Params"></a>

### Params
Params defines the parameters for the savings module.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `supported_denoms` | [string](#string) | repeated |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="kava/savings/v1beta1/genesis.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/savings/v1beta1/genesis.proto



<a name="kava.savings.v1beta1.GenesisState"></a>

### GenesisState
GenesisState defines the savings module's genesis state.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#kava.savings.v1beta1.Params) |  | params defines all the parameters of the module. |
| `deposits` | [Deposit](#kava.savings.v1beta1.Deposit) | repeated |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="kava/savings/v1beta1/query.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/savings/v1beta1/query.proto



<a name="kava.savings.v1beta1.QueryDepositsRequest"></a>

### QueryDepositsRequest
QueryDepositsRequest defines the request type for querying x/savings
deposits.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `denom` | [string](#string) |  |  |
| `owner` | [string](#string) |  |  |
| `pagination` | [cosmos.base.query.v1beta1.PageRequest](#cosmos.base.query.v1beta1.PageRequest) |  |  |






<a name="kava.savings.v1beta1.QueryDepositsResponse"></a>

### QueryDepositsResponse
QueryDepositsResponse defines the response type for querying x/savings
deposits.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `deposits` | [Deposit](#kava.savings.v1beta1.Deposit) | repeated |  |
| `pagination` | [cosmos.base.query.v1beta1.PageResponse](#cosmos.base.query.v1beta1.PageResponse) |  |  |






<a name="kava.savings.v1beta1.QueryParamsRequest"></a>

### QueryParamsRequest
QueryParamsRequest defines the request type for querying x/savings
parameters.






<a name="kava.savings.v1beta1.QueryParamsResponse"></a>

### QueryParamsResponse
QueryParamsResponse defines the response type for querying x/savings
parameters.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#kava.savings.v1beta1.Params) |  |  |






<a name="kava.savings.v1beta1.QueryTotalSupplyRequest"></a>

### QueryTotalSupplyRequest
QueryTotalSupplyRequest defines the request type for Query/TotalSupply method.






<a name="kava.savings.v1beta1.QueryTotalSupplyResponse"></a>

### QueryTotalSupplyResponse
TotalSupplyResponse defines the response type for the Query/TotalSupply method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `height` | [int64](#int64) |  | Height is the block height at which these totals apply |
| `result` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) | repeated | Result is a list of coins supplied to savings |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="kava.savings.v1beta1.Query"></a>

### Query
Query defines the gRPC querier service for savings module

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `Params` | [QueryParamsRequest](#kava.savings.v1beta1.QueryParamsRequest) | [QueryParamsResponse](#kava.savings.v1beta1.QueryParamsResponse) | Params queries all parameters of the savings module. | GET|/kava/savings/v1beta1/params|
| `Deposits` | [QueryDepositsRequest](#kava.savings.v1beta1.QueryDepositsRequest) | [QueryDepositsResponse](#kava.savings.v1beta1.QueryDepositsResponse) | Deposits queries savings deposits. | GET|/kava/savings/v1beta1/deposits|
| `TotalSupply` | [QueryTotalSupplyRequest](#kava.savings.v1beta1.QueryTotalSupplyRequest) | [QueryTotalSupplyResponse](#kava.savings.v1beta1.QueryTotalSupplyResponse) | TotalSupply returns the total sum of all coins currently locked into the savings module. | GET|/kava/savings/v1beta1/total_supply|

 <!-- end services -->



<a name="kava/savings/v1beta1/tx.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/savings/v1beta1/tx.proto



<a name="kava.savings.v1beta1.MsgDeposit"></a>

### MsgDeposit
MsgDeposit defines the Msg/Deposit request type.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `depositor` | [string](#string) |  |  |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) | repeated |  |






<a name="kava.savings.v1beta1.MsgDepositResponse"></a>

### MsgDepositResponse
MsgDepositResponse defines the Msg/Deposit response type.






<a name="kava.savings.v1beta1.MsgWithdraw"></a>

### MsgWithdraw
MsgWithdraw defines the Msg/Withdraw request type.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `depositor` | [string](#string) |  |  |
| `amount` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) | repeated |  |






<a name="kava.savings.v1beta1.MsgWithdrawResponse"></a>

### MsgWithdrawResponse
MsgWithdrawResponse defines the Msg/Withdraw response type.





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="kava.savings.v1beta1.Msg"></a>

### Msg
Msg defines the savings Msg service.

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `Deposit` | [MsgDeposit](#kava.savings.v1beta1.MsgDeposit) | [MsgDepositResponse](#kava.savings.v1beta1.MsgDepositResponse) | Deposit defines a method for depositing funds to the savings module account | |
| `Withdraw` | [MsgWithdraw](#kava.savings.v1beta1.MsgWithdraw) | [MsgWithdrawResponse](#kava.savings.v1beta1.MsgWithdrawResponse) | Withdraw defines a method for withdrawing funds to the savings module account | |

 <!-- end services -->



<a name="kava/swap/v1beta1/swap.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/swap/v1beta1/swap.proto



<a name="kava.swap.v1beta1.AllowedPool"></a>

### AllowedPool
AllowedPool defines a pool that is allowed to be created


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `token_a` | [string](#string) |  | token_a represents the a token allowed |
| `token_b` | [string](#string) |  | token_b represents the b token allowed |






<a name="kava.swap.v1beta1.Params"></a>

### Params
Params defines the parameters for the swap module.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `allowed_pools` | [AllowedPool](#kava.swap.v1beta1.AllowedPool) | repeated | allowed_pools defines that pools that are allowed to be created |
| `swap_fee` | [string](#string) |  | swap_fee defines the swap fee for all pools |






<a name="kava.swap.v1beta1.PoolRecord"></a>

### PoolRecord
PoolRecord represents the state of a liquidity pool
and is used to store the state of a denominated pool


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `pool_id` | [string](#string) |  | pool_id represents the unique id of the pool |
| `reserves_a` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | reserves_a is the a token coin reserves |
| `reserves_b` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | reserves_b is the a token coin reserves |
| `total_shares` | [string](#string) |  | total_shares is the total distrubuted shares of the pool |






<a name="kava.swap.v1beta1.ShareRecord"></a>

### ShareRecord
ShareRecord stores the shares owned for a depositor and pool


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `depositor` | [bytes](#bytes) |  | depositor represents the owner of the shares |
| `pool_id` | [string](#string) |  | pool_id represents the pool the shares belong to |
| `shares_owned` | [string](#string) |  | shares_owned represents the number of shares owned by depsoitor for the pool_id |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="kava/swap/v1beta1/genesis.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/swap/v1beta1/genesis.proto



<a name="kava.swap.v1beta1.GenesisState"></a>

### GenesisState
GenesisState defines the swap module's genesis state.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#kava.swap.v1beta1.Params) |  | params defines all the parameters related to swap |
| `pool_records` | [PoolRecord](#kava.swap.v1beta1.PoolRecord) | repeated | pool_records defines the available pools |
| `share_records` | [ShareRecord](#kava.swap.v1beta1.ShareRecord) | repeated | share_records defines the owned shares of each pool |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->

 <!-- end services -->



<a name="kava/swap/v1beta1/query.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/swap/v1beta1/query.proto



<a name="kava.swap.v1beta1.DepositResponse"></a>

### DepositResponse
DepositResponse defines a single deposit query response type.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `depositor` | [string](#string) |  | depositor represents the owner of the deposit |
| `pool_id` | [string](#string) |  | pool_id represents the pool the deposit is for |
| `shares_owned` | [string](#string) |  | shares_owned presents the shares owned by the depositor for the pool |
| `shares_value` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) | repeated | shares_value represents the coin value of the shares_owned |






<a name="kava.swap.v1beta1.PoolResponse"></a>

### PoolResponse
Pool represents the state of a single pool


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `name` | [string](#string) |  | name represents the name of the pool |
| `coins` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) | repeated | coins represents the total reserves of the pool |
| `total_shares` | [string](#string) |  | total_shares represents the total shares of the pool |






<a name="kava.swap.v1beta1.QueryDepositsRequest"></a>

### QueryDepositsRequest
QueryDepositsRequest is the request type for the Query/Deposits RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `owner` | [string](#string) |  | owner optionally filters deposits by owner |
| `pool_id` | [string](#string) |  | pool_id optionally fitlers deposits by pool id |
| `pagination` | [cosmos.base.query.v1beta1.PageRequest](#cosmos.base.query.v1beta1.PageRequest) |  | pagination defines an optional pagination for the request. |






<a name="kava.swap.v1beta1.QueryDepositsResponse"></a>

### QueryDepositsResponse
QueryDepositsResponse is the response type for the Query/Deposits RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `deposits` | [DepositResponse](#kava.swap.v1beta1.DepositResponse) | repeated | deposits returns the deposits matching the requested parameters |
| `pagination` | [cosmos.base.query.v1beta1.PageResponse](#cosmos.base.query.v1beta1.PageResponse) |  | pagination defines the pagination in the response. |






<a name="kava.swap.v1beta1.QueryParamsRequest"></a>

### QueryParamsRequest
QueryParamsRequest defines the request type for querying x/swap parameters.






<a name="kava.swap.v1beta1.QueryParamsResponse"></a>

### QueryParamsResponse
QueryParamsResponse defines the response type for querying x/swap parameters.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `params` | [Params](#kava.swap.v1beta1.Params) |  | params represents the swap module parameters |






<a name="kava.swap.v1beta1.QueryPoolsRequest"></a>

### QueryPoolsRequest
QueryPoolsRequest is the request type for the Query/Pools RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `pool_id` | [string](#string) |  | pool_id filters pools by id |
| `pagination` | [cosmos.base.query.v1beta1.PageRequest](#cosmos.base.query.v1beta1.PageRequest) |  | pagination defines an optional pagination for the request. |






<a name="kava.swap.v1beta1.QueryPoolsResponse"></a>

### QueryPoolsResponse
QueryPoolsResponse is the response type for the Query/Pools RPC method.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `pools` | [PoolResponse](#kava.swap.v1beta1.PoolResponse) | repeated | pools represents returned pools |
| `pagination` | [cosmos.base.query.v1beta1.PageResponse](#cosmos.base.query.v1beta1.PageResponse) |  | pagination defines the pagination in the response. |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="kava.swap.v1beta1.Query"></a>

### Query
Query defines the gRPC querier service for swap module

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `Params` | [QueryParamsRequest](#kava.swap.v1beta1.QueryParamsRequest) | [QueryParamsResponse](#kava.swap.v1beta1.QueryParamsResponse) | Params queries all parameters of the swap module. | GET|/kava/swap/v1beta1/params|
| `Pools` | [QueryPoolsRequest](#kava.swap.v1beta1.QueryPoolsRequest) | [QueryPoolsResponse](#kava.swap.v1beta1.QueryPoolsResponse) | Pools queries pools based on pool ID | GET|/kava/swap/v1beta1/pools|
| `Deposits` | [QueryDepositsRequest](#kava.swap.v1beta1.QueryDepositsRequest) | [QueryDepositsResponse](#kava.swap.v1beta1.QueryDepositsResponse) | Deposits queries deposit details based on owner address and pool | GET|/kava/swap/v1beta1/deposits|

 <!-- end services -->



<a name="kava/swap/v1beta1/tx.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/swap/v1beta1/tx.proto



<a name="kava.swap.v1beta1.MsgDeposit"></a>

### MsgDeposit
MsgDeposit represents a message for depositing liquidity into a pool


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `depositor` | [string](#string) |  | depositor represents the address to deposit funds from |
| `token_a` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | token_a represents one token of deposit pair |
| `token_b` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | token_b represents one token of deposit pair |
| `slippage` | [string](#string) |  | slippage represents the max decimal percentage price change |
| `deadline` | [int64](#int64) |  | deadline represents the unix timestamp to complete the deposit by |






<a name="kava.swap.v1beta1.MsgDepositResponse"></a>

### MsgDepositResponse
MsgDepositResponse defines the Msg/Deposit response type.






<a name="kava.swap.v1beta1.MsgSwapExactForTokens"></a>

### MsgSwapExactForTokens
MsgSwapExactForTokens represents a message for trading exact coinA for coinB


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `requester` | [string](#string) |  | represents the address swaping the tokens |
| `exact_token_a` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | exact_token_a represents the exact amount to swap for token_b |
| `token_b` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | token_b represents the desired token_b to swap for |
| `slippage` | [string](#string) |  | slippage represents the maximum change in token_b allowed |
| `deadline` | [int64](#int64) |  | deadline represents the unix timestamp to complete the swap by |






<a name="kava.swap.v1beta1.MsgSwapExactForTokensResponse"></a>

### MsgSwapExactForTokensResponse
MsgSwapExactForTokensResponse defines the Msg/SwapExactForTokens response
type.






<a name="kava.swap.v1beta1.MsgSwapForExactTokens"></a>

### MsgSwapForExactTokens
MsgSwapForExactTokens represents a message for trading coinA for an exact
coinB


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `requester` | [string](#string) |  | represents the address swaping the tokens |
| `token_a` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | token_a represents the desired token_a to swap for |
| `exact_token_b` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | exact_token_b represents the exact token b amount to swap for token a |
| `slippage` | [string](#string) |  | slippage represents the maximum change in token_a allowed |
| `deadline` | [int64](#int64) |  | deadline represents the unix timestamp to complete the swap by |






<a name="kava.swap.v1beta1.MsgSwapForExactTokensResponse"></a>

### MsgSwapForExactTokensResponse
MsgSwapForExactTokensResponse defines the Msg/SwapForExactTokensResponse
response type.






<a name="kava.swap.v1beta1.MsgWithdraw"></a>

### MsgWithdraw
MsgWithdraw represents a message for withdrawing liquidity from a pool


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `from` | [string](#string) |  | from represents the address we are withdrawing for |
| `shares` | [string](#string) |  | shares represents the amount of shares to withdraw |
| `min_token_a` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | min_token_a represents the minimum a token to withdraw |
| `min_token_b` | [cosmos.base.v1beta1.Coin](#cosmos.base.v1beta1.Coin) |  | min_token_a represents the minimum a token to withdraw |
| `deadline` | [int64](#int64) |  | deadline represents the unix timestamp to complete the withdraw by |






<a name="kava.swap.v1beta1.MsgWithdrawResponse"></a>

### MsgWithdrawResponse
MsgWithdrawResponse defines the Msg/Withdraw response type.





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="kava.swap.v1beta1.Msg"></a>

### Msg
Msg defines the swap Msg service.

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `Deposit` | [MsgDeposit](#kava.swap.v1beta1.MsgDeposit) | [MsgDepositResponse](#kava.swap.v1beta1.MsgDepositResponse) | Deposit defines a method for depositing liquidity into a pool | |
| `Withdraw` | [MsgWithdraw](#kava.swap.v1beta1.MsgWithdraw) | [MsgWithdrawResponse](#kava.swap.v1beta1.MsgWithdrawResponse) | Withdraw defines a method for withdrawing liquidity into a pool | |
| `SwapExactForTokens` | [MsgSwapExactForTokens](#kava.swap.v1beta1.MsgSwapExactForTokens) | [MsgSwapExactForTokensResponse](#kava.swap.v1beta1.MsgSwapExactForTokensResponse) | SwapExactForTokens represents a message for trading exact coinA for coinB | |
| `SwapForExactTokens` | [MsgSwapForExactTokens](#kava.swap.v1beta1.MsgSwapForExactTokens) | [MsgSwapForExactTokensResponse](#kava.swap.v1beta1.MsgSwapForExactTokensResponse) | SwapForExactTokens represents a message for trading coinA for an exact coinB | |

 <!-- end services -->



<a name="kava/validatorvesting/v1beta1/query.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## kava/validatorvesting/v1beta1/query.proto



<a name="kava.validatorvesting.v1beta1.QueryCirculatingSupplyHARDRequest"></a>

### QueryCirculatingSupplyHARDRequest
QueryCirculatingSupplyHARDRequest is the request type for the Query/CirculatingSupplyHARD RPC method






<a name="kava.validatorvesting.v1beta1.QueryCirculatingSupplyHARDResponse"></a>

### QueryCirculatingSupplyHARDResponse
QueryCirculatingSupplyHARDResponse is the response type for the Query/CirculatingSupplyHARD RPC method


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `amount` | [string](#string) |  |  |






<a name="kava.validatorvesting.v1beta1.QueryCirculatingSupplyRequest"></a>

### QueryCirculatingSupplyRequest
QueryCirculatingSupplyRequest is the request type for the Query/CirculatingSupply RPC method






<a name="kava.validatorvesting.v1beta1.QueryCirculatingSupplyResponse"></a>

### QueryCirculatingSupplyResponse
QueryCirculatingSupplyResponse is the response type for the Query/CirculatingSupply RPC method


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `amount` | [string](#string) |  |  |






<a name="kava.validatorvesting.v1beta1.QueryCirculatingSupplySWPRequest"></a>

### QueryCirculatingSupplySWPRequest
QueryCirculatingSupplySWPRequest is the request type for the Query/CirculatingSupplySWP RPC method






<a name="kava.validatorvesting.v1beta1.QueryCirculatingSupplySWPResponse"></a>

### QueryCirculatingSupplySWPResponse
QueryCirculatingSupplySWPResponse is the response type for the Query/CirculatingSupplySWP RPC method


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `amount` | [string](#string) |  |  |






<a name="kava.validatorvesting.v1beta1.QueryCirculatingSupplyUSDXRequest"></a>

### QueryCirculatingSupplyUSDXRequest
QueryCirculatingSupplyUSDXRequest is the request type for the Query/CirculatingSupplyUSDX RPC method






<a name="kava.validatorvesting.v1beta1.QueryCirculatingSupplyUSDXResponse"></a>

### QueryCirculatingSupplyUSDXResponse
QueryCirculatingSupplyUSDXResponse is the response type for the Query/CirculatingSupplyUSDX RPC method


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `amount` | [string](#string) |  |  |






<a name="kava.validatorvesting.v1beta1.QueryTotalSupplyHARDRequest"></a>

### QueryTotalSupplyHARDRequest
QueryTotalSupplyHARDRequest is the request type for the Query/TotalSupplyHARD RPC method






<a name="kava.validatorvesting.v1beta1.QueryTotalSupplyHARDResponse"></a>

### QueryTotalSupplyHARDResponse
QueryTotalSupplyHARDResponse is the response type for the Query/TotalSupplyHARD RPC method


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `amount` | [string](#string) |  |  |






<a name="kava.validatorvesting.v1beta1.QueryTotalSupplyRequest"></a>

### QueryTotalSupplyRequest
QueryTotalSupplyRequest is the request type for the Query/TotalSupply RPC method






<a name="kava.validatorvesting.v1beta1.QueryTotalSupplyResponse"></a>

### QueryTotalSupplyResponse
QueryTotalSupplyResponse is the response type for the Query/TotalSupply RPC method


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `amount` | [string](#string) |  |  |






<a name="kava.validatorvesting.v1beta1.QueryTotalSupplyUSDXRequest"></a>

### QueryTotalSupplyUSDXRequest
QueryTotalSupplyUSDXRequest is the request type for the Query/TotalSupplyUSDX RPC method






<a name="kava.validatorvesting.v1beta1.QueryTotalSupplyUSDXResponse"></a>

### QueryTotalSupplyUSDXResponse
QueryTotalSupplyUSDXResponse is the response type for the Query/TotalSupplyUSDX RPC method


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| `amount` | [string](#string) |  |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="kava.validatorvesting.v1beta1.Query"></a>

### Query
Query defines the gRPC querier service for validator-vesting module

| Method Name | Request Type | Response Type | Description | HTTP Verb | Endpoint |
| ----------- | ------------ | ------------- | ------------| ------- | -------- |
| `CirculatingSupply` | [QueryCirculatingSupplyRequest](#kava.validatorvesting.v1beta1.QueryCirculatingSupplyRequest) | [QueryCirculatingSupplyResponse](#kava.validatorvesting.v1beta1.QueryCirculatingSupplyResponse) | CirculatingSupply returns the total amount of kava tokens in circulation | GET|/kava/validator-vesting/v1beta1/circulating_supply|
| `TotalSupply` | [QueryTotalSupplyRequest](#kava.validatorvesting.v1beta1.QueryTotalSupplyRequest) | [QueryTotalSupplyResponse](#kava.validatorvesting.v1beta1.QueryTotalSupplyResponse) | TotalSupply returns the total amount of kava tokens | GET|/kava/validator-vesting/v1beta1/total_supply|
| `CirculatingSupplyHARD` | [QueryCirculatingSupplyHARDRequest](#kava.validatorvesting.v1beta1.QueryCirculatingSupplyHARDRequest) | [QueryCirculatingSupplyHARDResponse](#kava.validatorvesting.v1beta1.QueryCirculatingSupplyHARDResponse) | CirculatingSupplyHARD returns the total amount of hard tokens in circulation | GET|/kava/validator-vesting/v1beta1/circulating_supply_hard|
| `CirculatingSupplyUSDX` | [QueryCirculatingSupplyUSDXRequest](#kava.validatorvesting.v1beta1.QueryCirculatingSupplyUSDXRequest) | [QueryCirculatingSupplyUSDXResponse](#kava.validatorvesting.v1beta1.QueryCirculatingSupplyUSDXResponse) | CirculatingSupplyUSDX returns the total amount of usdx tokens in circulation | GET|/kava/validator-vesting/v1beta1/circulating_supply_usdx|
| `CirculatingSupplySWP` | [QueryCirculatingSupplySWPRequest](#kava.validatorvesting.v1beta1.QueryCirculatingSupplySWPRequest) | [QueryCirculatingSupplySWPResponse](#kava.validatorvesting.v1beta1.QueryCirculatingSupplySWPResponse) | CirculatingSupplySWP returns the total amount of swp tokens in circulation | GET|/kava/validator-vesting/v1beta1/circulating_supply_swp|
| `TotalSupplyHARD` | [QueryTotalSupplyHARDRequest](#kava.validatorvesting.v1beta1.QueryTotalSupplyHARDRequest) | [QueryTotalSupplyHARDResponse](#kava.validatorvesting.v1beta1.QueryTotalSupplyHARDResponse) | TotalSupplyHARD returns the total amount of hard tokens | GET|/kava/validator-vesting/v1beta1/total_supply_hard|
| `TotalSupplyUSDX` | [QueryTotalSupplyUSDXRequest](#kava.validatorvesting.v1beta1.QueryTotalSupplyUSDXRequest) | [QueryTotalSupplyUSDXResponse](#kava.validatorvesting.v1beta1.QueryTotalSupplyUSDXResponse) | TotalSupplyUSDX returns the total amount of usdx tokens | GET|/kava/validator-vesting/v1beta1/total_supply_usdx|

 <!-- end services -->



## Scalar Value Types

| .proto Type | Notes | C++ | Java | Python | Go | C# | PHP | Ruby |
| ----------- | ----- | --- | ---- | ------ | -- | -- | --- | ---- |
| <a name="double" /> double |  | double | double | float | float64 | double | float | Float |
| <a name="float" /> float |  | float | float | float | float32 | float | float | Float |
| <a name="int32" /> int32 | Uses variable-length encoding. Inefficient for encoding negative numbers – if your field is likely to have negative values, use sint32 instead. | int32 | int | int | int32 | int | integer | Bignum or Fixnum (as required) |
| <a name="int64" /> int64 | Uses variable-length encoding. Inefficient for encoding negative numbers – if your field is likely to have negative values, use sint64 instead. | int64 | long | int/long | int64 | long | integer/string | Bignum |
| <a name="uint32" /> uint32 | Uses variable-length encoding. | uint32 | int | int/long | uint32 | uint | integer | Bignum or Fixnum (as required) |
| <a name="uint64" /> uint64 | Uses variable-length encoding. | uint64 | long | int/long | uint64 | ulong | integer/string | Bignum or Fixnum (as required) |
| <a name="sint32" /> sint32 | Uses variable-length encoding. Signed int value. These more efficiently encode negative numbers than regular int32s. | int32 | int | int | int32 | int | integer | Bignum or Fixnum (as required) |
| <a name="sint64" /> sint64 | Uses variable-length encoding. Signed int value. These more efficiently encode negative numbers than regular int64s. | int64 | long | int/long | int64 | long | integer/string | Bignum |
| <a name="fixed32" /> fixed32 | Always four bytes. More efficient than uint32 if values are often greater than 2^28. | uint32 | int | int | uint32 | uint | integer | Bignum or Fixnum (as required) |
| <a name="fixed64" /> fixed64 | Always eight bytes. More efficient than uint64 if values are often greater than 2^56. | uint64 | long | int/long | uint64 | ulong | integer/string | Bignum |
| <a name="sfixed32" /> sfixed32 | Always four bytes. | int32 | int | int | int32 | int | integer | Bignum or Fixnum (as required) |
| <a name="sfixed64" /> sfixed64 | Always eight bytes. | int64 | long | int/long | int64 | long | integer/string | Bignum |
| <a name="bool" /> bool |  | bool | boolean | boolean | bool | bool | boolean | TrueClass/FalseClass |
| <a name="string" /> string | A string must always contain UTF-8 encoded or 7-bit ASCII text. | string | String | str/unicode | string | string | string | String (UTF-8) |
| <a name="bytes" /> bytes | May contain any arbitrary sequence of bytes. | string | ByteString | str | []byte | ByteString | string | String (ASCII-8BIT) |

