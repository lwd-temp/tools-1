# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/css-parser/index.test.ts --update-snapshots` to update.

## `keyframe`

### `ast`

```javascript
CSSRoot {
	body: [
		CSSAtRule {
			name: "keyframes"
			prelude: []
			block: CSSKeyframe {
				value: [
					CSSKeyframeBlock {
						value: [
							CSSDeclaration {
								name: "margin-top"
								value: [
									CSSDimension {
										value: 50
										unit: "px"
										loc: SourceLocation keyframe/input.css 3:14-3:18
									}
								]
								important: true
								loc: SourceLocation keyframe/input.css 3:2-3:29
							}
						]
						name: CSSKeyframeSelector {
							value: CSSRaw {
								value: "from"
								loc: SourceLocation keyframe/input.css 2:1-2:5
							}
							loc: SourceLocation keyframe/input.css 2:1-2:5
						}
						loc: SourceLocation keyframe/input.css 2:1-5:1
					}
					CSSKeyframeBlock {
						value: [
							CSSDeclaration {
								name: "margin-top"
								value: [
									CSSDimension {
										value: 100
										unit: "px"
										loc: SourceLocation keyframe/input.css 6:14-6:19
									}
								]
								important: true
								loc: SourceLocation keyframe/input.css 6:2-6:30
							}
						]
						name: CSSKeyframeSelector {
							value: CSSRaw {
								value: "to"
								loc: SourceLocation keyframe/input.css 5:1-5:3
							}
							loc: SourceLocation keyframe/input.css 5:1-5:3
						}
						loc: SourceLocation keyframe/input.css 5:1-8:0
					}
				]
				name: CSSKeyframeName {
					value: CSSRaw {
						value: "important1"
						loc: SourceLocation keyframe/input.css 1:11-1:21
					}
					loc: SourceLocation keyframe/input.css 1:11-1:21
				}
				loc: SourceLocation keyframe/input.css 1:10-8:1
			}
			loc: SourceLocation keyframe/input.css 1:0-8:1
		}
		CSSAtRule {
			name: "keyframes"
			prelude: []
			block: CSSKeyframe {
				value: [
					CSSKeyframeBlock {
						value: []
						name: CSSKeyframeSelector {
							value: CSSRaw {
								value: "from"
								loc: SourceLocation keyframe/input.css 11:1-11:5
							}
							loc: SourceLocation keyframe/input.css 11:1-11:5
						}
						loc: SourceLocation keyframe/input.css 11:1-12:1
					}
					CSSKeyframeBlock {
						value: []
						name: CSSKeyframeSelector {
							value: CSSRaw {
								value: "to"
								loc: SourceLocation keyframe/input.css 12:1-12:3
							}
							loc: SourceLocation keyframe/input.css 12:1-12:3
						}
						loc: SourceLocation keyframe/input.css 12:1-13:1
					}
					CSSKeyframeBlock {
						value: []
						name: CSSKeyframeSelector {
							value: CSSPercentage {
								value: 15
								loc: SourceLocation keyframe/input.css 13:1-13:4
							}
							loc: SourceLocation keyframe/input.css 13:1-13:4
						}
						loc: SourceLocation keyframe/input.css 13:1-14:1
					}
					CSSKeyframeBlock {
						value: []
						name: CSSKeyframeSelector {
							value: CSSPercentage {
								value: 0
								loc: SourceLocation keyframe/input.css 14:1-14:3
							}
							loc: SourceLocation keyframe/input.css 14:1-14:3
						}
						loc: SourceLocation keyframe/input.css 14:1-15:1
					}
					CSSKeyframeBlock {
						value: []
						name: CSSKeyframeSelector {
							value: CSSPercentage {
								value: 100
								loc: SourceLocation keyframe/input.css 15:1-15:5
							}
							loc: SourceLocation keyframe/input.css 15:1-15:5
						}
						loc: SourceLocation keyframe/input.css 15:1-16:0
					}
				]
				name: CSSKeyframeName {
					value: CSSRaw {
						value: "foo"
						loc: SourceLocation keyframe/input.css 10:11-10:14
					}
					loc: SourceLocation keyframe/input.css 10:11-10:14
				}
				loc: SourceLocation keyframe/input.css 10:10-16:1
			}
			loc: SourceLocation keyframe/input.css 10:0-16:1
		}
		CSSAtRule {
			name: "keyframes"
			prelude: []
			block: CSSKeyframe {
				value: []
				name: CSSKeyframeName {
					value: CSSString {
						value: "foo"
						loc: SourceLocation keyframe/input.css 18:11-18:16
					}
					loc: SourceLocation keyframe/input.css 18:11-18:16
				}
				loc: SourceLocation keyframe/input.css 18:10-20:1
			}
			loc: SourceLocation keyframe/input.css 18:0-20:1
		}
		CSSAtRule {
			name: "keyframes"
			prelude: []
			block: CSSKeyframe {
				value: []
				name: CSSKeyframeName {
					value: CSSString {
						value: "Initial"
						loc: SourceLocation keyframe/input.css 22:11-22:20
					}
					loc: SourceLocation keyframe/input.css 22:11-22:20
				}
				loc: SourceLocation keyframe/input.css 22:10-24:1
			}
			loc: SourceLocation keyframe/input.css 22:0-24:1
		}
		CSSAtRule {
			name: "keyframes"
			prelude: []
			block: CSSKeyframe {
				value: []
				name: CSSKeyframeName {
					value: CSSRaw {
						value: "FOO"
						loc: SourceLocation keyframe/input.css 26:11-26:14
					}
					loc: SourceLocation keyframe/input.css 26:11-26:14
				}
				loc: SourceLocation keyframe/input.css 26:10-27:1
			}
			loc: SourceLocation keyframe/input.css 26:0-27:1
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	path: UIDPath<keyframe/input.css>
	loc: SourceLocation keyframe/input.css 1:0-27:1
}
```

### `diagnostics`

```

```