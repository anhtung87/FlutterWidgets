# Column Class

**Column** là 1 Widget hiển thị các children theo chiều dọc.
Nếu muốn widget children lấp đầy không gian bên trong Column, bọc 1 widget child
bên trong 1 class **Expand**
**Column** không thể cuộn. Nếu muốn dùng cuộn, hãy sử dụng **ListView**
Nếu **Column** chỉ có 1 child, xem xét đến việc sử dụng **Align** hoặc **Center**
để căn chỉnh vị trí của child.

## Kế thừa

Object > DiagnosticableTree > Widget > RenderObjectWidget > MultiChildRenderObjectWidget > Flex > Column

## Properties

> children -> List<Widget>

> crossAxisAlignment -> CrossAxisAlignment
> Cách thể hiện của các child bên trong
> VD:
> - CrossAxisAlignment.baseline
> - CrossAxisAlignmnet.center

> direction -> Axis

> hashCode -> int

> key -> Key

> mainAxisAlignment -> MainAxisAlignment

> mainAxisSize -> MainAxisSize

> runtimeType -> Type

> textBaseline -> TextBaseline

> textDirection -> TextDirection

> verticalDirection -> VerticalDirection


## Methods

> createElement() -> MultiChildRenderObjectElement

> createRenderObject(BuildContext Context) -> RenderFlex

> debugDescribeChildren() -> List<DiagnosticsNode>

> debugFillProperties(DiagnosticsPropertiesBuilder properties) -> void

> didUnmountRenderObject(covariant RenderObject renderObject) -> void

> getEffectiveTextDirection(BuildContext context) -> TextDirection

> noSuchMethod(Invocation invocation) -> dynamic

> toDiagnosticsNode(String name, DiagnosticsTreeStyle style) -> DiagnosticsNode

> toString(DiagnosticLevel minLevel: DiagnosticLevel.info) -> String

> toStringDeep({String prefixLineOne: '', String prefixOtherLines, DiagnosticLevel minLevel: DiagnosticLevel.debug}) -> String

> toStringShallow({String joiner:',', DiagnosticLevel minLevel: DiagnosticLevel.debug}) -> String

> toStringShort() -> String

>updateRenderObject(BuildContext context, convariant RenderFlex renderObject) -> Void