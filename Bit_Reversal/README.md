# Bit Reversal Spec

Implement functions to reverse the bit order of unsigned integers for the following widths:
- 8-bit (`uint8_t`)
- 16-bit (`uint16_t`)
- 32-bit (`uint32_t`)

## What is Bit Reversal?
Given an N-bit value, bit reversal means flipping the order of its bits:
- Example: `0b11010000` (0xD0) reversed (8-bit) is `0b00001011` (0x0B)

## Required Functions
```c
uint8_t  reverse8(uint8_t x);
uint16_t reverse16(uint16_t x);
uint32_t reverse32(uint32_t x);
```

## Constraints
- No dynamic memory allocation
- No external dependencies
- Must work for all possible input values

## Notes
- Focus on efficiency and portability
- Provide simple, self-contained C code 