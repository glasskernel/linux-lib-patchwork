# linux-lib-patchwork

Patch collection and reproduction scripts for the Linux kernel `lib/` directory.

## Layout

- `pending/`: Patches currently under review or development.
- `upstreamed/`: Patches accepted into a parent tree.
- `reproducers/`: Scripts and logs for verifying bugs.

## Current Patches

### Pending
- `0000-cover-letter-fsmids.patch`: Fixes to a IDS evasion
- `0001-lib-asn1_encoder-fix-corrupted-ASN.1-OID-encoding-fo.patch`: lib/asn1_encoder: fix corrupted ASN.1 OID encoding for zero
- `0001-lib-base64-fix-out-of-bounds-read-with-negative-stri.patch`: lib/base64: fix out-of-bounds read with negative string
- `0001-lib-bitmap-Fix-out-of-bounds-memory-corruption-in-bi.patch`: lib/bitmap: Fix out-of-bounds memory corruption in bitmap
- `0001-lib-btree-optimize-btree_merge.patch`: lib/btree: optimize btree_merge
- `0001-lib-decompress-track-total-bytes-consumed-with-fill-.patch`: lib/decompress: track total bytes consumed with fill function
- `0001-lib-glob-fix-dangling-backslash-matching-null-termin.patch`: lib/glob: fix dangling backslash matching null terminator
- `0001-lib-inflate-fix-hardcoded-4-byte-malloc-alignment.patch`: lib/inflate: fix hardcoded 4-byte malloc alignment
- `0001-lib-kfifo-fix-integer-underflow-in-kfifo_init-buffer.patch`: lib/kfifo: fix integer underflow in kfifo_init buffer size
- `0001-lib-logic_iomem-add-bounds-check-to-prevent-overlapp.patch`: lib/logic_iomem: add bounds check to prevent overlapping
- `0001-lib-logic_pio-add-missing-bounds-check-in-logic_pio_.patch`: lib/logic_pio: add missing bounds check in
- `0001-lib-ts_fsm-Fix-text-search-evasion-on-block-boundari.patch`: lib/ts_fsm: Fix text search evasion on block boundaries
- `0001-lib-ubsan-fix-out-of-bounds-array-access-in-type_che.patch`: lib/ubsan: fix out-of-bounds array access in type_check_kinds
- `0002-lib-ts_fsm-Remove-overeager-end-of-data-check.patch`: lib/ts_fsm: Remove overeager end-of-data check
- `debugobjects_null_deref.patch`: debugobjects: fix NULL obj_cache dereference in
- `idr_leak_error_path.patch`: lib/idr: fix memory leak on error path
- `idr_leak_inline_alloc.patch`: lib/idr: fix memory leak on inline allocation
- `ts_fsm_alloc_overflow.patch`: lib/ts_fsm: fix integer overflow in allocation size

### Upstreamed
- `bm_overflow.patch`: lib/ts_bm: fix integer overflow in pattern length calculation
- `kmp_overflow.patch`: lib/ts_kmp: fix integer overflow in pattern length

## Reproducers
- `repro_iptables.sh`
- `results.txt`
