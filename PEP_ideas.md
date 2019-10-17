
In this page I plan to list all PEP ideas that I encountered while developing the various libraries available in this repository.

## from `valid8` and `pyfields`

 * (to complete) the use case about multiple callback signature support, duck typing vs. `TypeError`. Proposal of an `InvalidArgSpecError` or `InvalidrgsError`.

## from `pyfields`

 * descriptors with only the `__set__` and not the `__get__`. That way attribute access could be extremely fast, while allowing for type and value validation. See https://github.com/smarie/python-pyfields/issues/18 
 * ability to override slots (see https://github.com/smarie/python-pyfields/issues/19)
 
