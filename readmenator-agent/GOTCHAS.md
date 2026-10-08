# Gotchas

## God Nodes (high connectivity)

These files have the most connections. Changes here have high blast radius.

- `neurologos_tricameral_loss5.4.py` (score: 10.30)
- `neurologos_tricameral_loss2.7.py` (score: 10.00)
- `neurologos_tricameral_loss8.0.py` (score: 9.50)
- `neurologos_tricameral_loss3.9.py` (score: 7.00)
- `neurologos_tricameral_loss4.5.py` (score: 5.10)
- `app.py` (score: 0.00)
- `install.sh` (score: 0.00)

## Hotspots (complexity + centrality)

- `neurologos_tricameral_loss5.4.py` -- complexity: 1.0, centrality: 1.0, combined: 1.0
- `neurologos_tricameral_loss8.0.py` -- complexity: 0.9, centrality: 1.0, combined: 1.0
- `neurologos_tricameral_loss2.7.py` -- complexity: 1.0, centrality: 0.9, combined: 0.9
- `neurologos_tricameral_loss3.9.py` -- complexity: 0.7, centrality: 0.5, combined: 0.6
- `neurologos_tricameral_loss4.5.py` -- complexity: 0.5, centrality: 0.5, combined: 0.5
- `app.py` -- complexity: 0.0, centrality: 0.0, combined: 0.0
- `install.sh` -- complexity: 0.0, centrality: 0.0, combined: 0.0

## Dataflow Issues (INFERRED, review each lead)

- `neurologos_tricameral_loss2.7.py:2308` `__getitem__` [UNCHECKED_ALLOC] `image`: Result of allocator stored in `image` is never checked against NULL.
- `neurologos_tricameral_loss3.9.py:1731` `__getitem__` [UNCHECKED_ALLOC] `image`: Result of allocator stored in `image` is never checked against NULL.
- `neurologos_tricameral_loss4.5.py:977` `__getitem__` [UNCHECKED_ALLOC] `image`: Result of allocator stored in `image` is never checked against NULL.
- `neurologos_tricameral_loss5.4.py:2616` `__getitem__` [UNCHECKED_ALLOC] `image`: Result of allocator stored in `image` is never checked against NULL.
- `neurologos_tricameral_loss8.0.py:2531` `__getitem__` [UNCHECKED_ALLOC] `image`: Result of allocator stored in `image` is never checked against NULL.
