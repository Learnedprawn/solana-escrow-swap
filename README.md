# solana-escrow-swap

SPL token erro
Error:
^^^^ the trait `Discriminator` is not implemented for `anchor_spl::token_interf
solution:
https://stackoverflow.com/questions/78362485/anchor-shows-errors-no-associated-item-named-anchor-private-gen-idl-type-fo

this occurs when the struct TakeOffer is not properly defined
14 | #[program]
   | ^^^^^^^^^^ could not find `__client_accounts_take_offer` in the crate root

