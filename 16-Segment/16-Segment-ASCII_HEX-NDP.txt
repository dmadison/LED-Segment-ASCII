/*
 *  Project     Segmented LED Display - ASCII Library
 *  @author     David Madison
 *  @link       github.com/dmadison/Segmented-LED-Display-ASCII
 *  @license    MIT - Copyright (c) 2017 David Madison
 *
 * Permission is hereby granted, free of charge, to any person obtaining a copy
 * of this software and associated documentation files (the "Software"), to deal
 * in the Software without restriction, including without limitation the rights
 * to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 * copies of the Software, and to permit persons to whom the Software is
 * furnished to do so, subject to the following conditions:
 *
 * The above copyright notice and this permission notice shall be included in
 * all copies or substantial portions of the Software.
 *
 * THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 * IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 * FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 * AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 * LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 * OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 * THE SOFTWARE.
 *
 */
 
const uint16_t SixteenSegmentASCII[96] = {
	0x0000, /* (space) */
	0x000C, /* ! */
	0x0204, /* " */
	0xAA3C, /* # */
	0xAABB, /* $ */
	0xEE99, /* % */
	0x9371, /* & */
	0x0200, /* ' */
	0x1400, /* ( */
	0x4100, /* ) */
	0xFF00, /* * */
	0xAA00, /* + */
	0x4000, /* , */
	0x8800, /* - */
	0x1000, /* . */
	0x4400, /* / */
	0x44FF, /* 0 */
	0x040C, /* 1 */
	0x8877, /* 2 */
	0x083F, /* 3 */
	0x888C, /* 4 */
	0x90B3, /* 5 */
	0x88FB, /* 6 */
	0x000F, /* 7 */
	0x88FF, /* 8 */
	0x88BF, /* 9 */
	0x2200, /* : */
	0x4200, /* ; */
	0x9400, /* < */
	0x8830, /* = */
	0x4900, /* > */
	0x2807, /* ? */
	0x0AF7, /* @ */
	0x88CF, /* A */
	0x2A3F, /* B */
	0x00F3, /* C */
	0x223F, /* D */
	0x80F3, /* E */
	0x80C3, /* F */
	0x08FB, /* G */
	0x88CC, /* H */
	0x2233, /* I */
	0x007C, /* J */
	0x94C0, /* K */
	0x00F0, /* L */
	0x05CC, /* M */
	0x11CC, /* N */
	0x00FF, /* O */
	0x88C7, /* P */
	0x10FF, /* Q */
	0x98C7, /* R */
	0x88BB, /* S */
	0x2203, /* T */
	0x00FC, /* U */
	0x44C0, /* V */
	0x50CC, /* W */
	0x5500, /* X */
	0x88BC, /* Y */
	0x4433, /* Z */
	0x2212, /* [ */
	0x1100, /* \ */
	0x2221, /* ] */
	0x5000, /* ^ */
	0x0030, /* _ */
	0x0100, /* ` */
	0xA070, /* a */
	0xA0E0, /* b */
	0x8060, /* c */
	0x281C, /* d */
	0xC060, /* e */
	0xAA02, /* f */
	0xA2A1, /* g */
	0xA0C0, /* h */
	0x2000, /* i */
	0x2260, /* j */
	0x3600, /* k */
	0x00C0, /* l */
	0xA848, /* m */
	0xA040, /* n */
	0xA060, /* o */
	0x82C1, /* p */
	0xA281, /* q */
	0x8040, /* r */
	0xA0A1, /* s */
	0x80E0, /* t */
	0x2060, /* u */
	0x4040, /* v */
	0x5048, /* w */
	0x5500, /* x */
	0x0A1C, /* y */
	0xC020, /* z */
	0xA212, /* { */
	0x2200, /* | */
	0x2A21, /* } */
	0xCC00, /* ~ */
	0x0000, /* (del) */
};
