

# Class gallery\_relation\_editor



[**ClassList**](annotated.md) **>** [**gallery\_relation\_editor**](classgallery__relation__editor.md)








Inherits the following classes: [RelationEditorBase](classRelationEditorBase.md)


















































## Public Properties

| Type | Name |
| ---: | :--- |
| property int | [**documentViewer**](classgallery__relation__editor.md#property-documentviewer)  <br> |
| property string | [**imagePrefix**](classgallery__relation__editor.md#property-imageprefix)  <br> |
| property bool | [**isGridView**](classgallery__relation__editor.md#property-isgridview)  <br> |
| property [**ResourceSource**](classResourceSource.md) | [**resourceSource**](classgallery__relation__editor.md#property-resourcesource)  <br> |


## Public Properties inherited from RelationEditorBase

See [RelationEditorBase](classRelationEditorBase.md)

| Type | Name |
| ---: | :--- |
| property int | [**bottomMargin**](classRelationEditorBase.md#property-bottommargin)  <br> |
| property Menu | [**childMenu**](classRelationEditorBase.md#property-childmenu)  <br> |
| property [**QfDialog**](classTheme_1_1QfDialog.md) | [**deleteDialog**](classRelationEditorBase.md#property-deletedialog)  <br> |
| property [**EmbeddedFeatureForm**](classEmbeddedFeatureForm.md) | [**embeddedPopup**](classRelationEditorBase.md#property-embeddedpopup)  <br> |
| property alias | [**footer**](classRelationEditorBase.md#property-footer-12)  <br> |
| property alias | [**footerContent**](classRelationEditorBase.md#property-footercontent)  <br> |
| property alias | [**gridView**](classRelationEditorBase.md#property-gridview-12)  <br> |
| property alias | [**headerActions**](classRelationEditorBase.md#property-headeractions)  <br> |
| property alias | [**headerEntry**](classRelationEditorBase.md#property-headerentry-12)  <br> |
| property alias | [**itemCount**](classRelationEditorBase.md#property-itemcount)  <br> |
| property int | [**itemHeight**](classRelationEditorBase.md#property-itemheight)  <br> |
| property int | [**maximumVisibleItems**](classRelationEditorBase.md#property-maximumvisibleitems)  <br> |
| property var | [**relationEditorModel**](classRelationEditorBase.md#property-relationeditormodel)  <br> |
| property bool | [**showAllItems**](classRelationEditorBase.md#property-showallitems)  <br> |
| property bool | [**showSortButton**](classRelationEditorBase.md#property-showsortbutton)  <br> |


## Public Properties inherited from EditorWidgetBase

See [EditorWidgetBase](classEditorWidgetBase.md)

| Type | Name |
| ---: | :--- |
| property bool | [**hasMenu**](classEditorWidgetBase.md#property-hasmenu)  <br> |
| property bool | [**isEmpty**](classEditorWidgetBase.md#property-isempty)  <br> |
| property bool | [**isLoaded**](classEditorWidgetBase.md#property-isloaded)  <br> |
| property bool | [**isNull**](classEditorWidgetBase.md#property-isnull)  <br> |
| property Menu | [**menu**](classEditorWidgetBase.md#property-menu)  <br> |










## Public Signals inherited from RelationEditorBase

See [RelationEditorBase](classRelationEditorBase.md)

| Type | Name |
| ---: | :--- |
| signal void | [**toggleSortAction**](classRelationEditorBase.md#signal-togglesortaction)  <br> |


## Public Signals inherited from EditorWidgetBase

See [EditorWidgetBase](classEditorWidgetBase.md)

| Type | Name |
| ---: | :--- |
| signal void | [**requestBarcode**](classEditorWidgetBase.md#signal-requestbarcode) (var item) <br> |
| signal void | [**requestGeometry**](classEditorWidgetBase.md#signal-requestgeometry) (var item, var layer) <br> |
| signal void | [**requestJumpToPoint**](classEditorWidgetBase.md#signal-requestjumptopoint) (var center, real scale, bool handleMargins) <br> |
| signal void | [**valueChangeRequested**](classEditorWidgetBase.md#signal-valuechangerequested) (var value, bool isNull) <br> |








## Public Functions

| Type | Name |
| ---: | :--- |
|  void | [**captureAudio**](#function-captureaudio) () <br> |
|  void | [**capturePhoto**](#function-capturephoto) () <br> |
|  void | [**captureVideo**](#function-capturevideo) () <br> |


## Public Functions inherited from RelationEditorBase

See [RelationEditorBase](classRelationEditorBase.md)

| Type | Name |
| ---: | :--- |
|  void | [**ensureEmbeddedFormLoaded**](classRelationEditorBase.md#function-ensureembeddedformloaded) () <br> |
|  void | [**isActionEnabled**](classRelationEditorBase.md#function-isactionenabled) (buttonType) <br> |
|  void | [**requestedGeometryReceived**](classRelationEditorBase.md#function-requestedgeometryreceived) (geometry) <br> |
|  void | [**showAddFeaturePopup**](classRelationEditorBase.md#function-showaddfeaturepopup) (geometry) <br> |
|  void | [**showAtlasMenu**](classRelationEditorBase.md#function-showatlasmenu) () <br> |


















































































## Public Properties Documentation




### property documentViewer 

```C++
int gallery_relation_editor::documentViewer;
```




<hr>



### property imagePrefix 

```C++
string gallery_relation_editor::imagePrefix;
```




<hr>



### property isGridView 

```C++
bool gallery_relation_editor::isGridView;
```




<hr>



### property resourceSource 

```C++
ResourceSource gallery_relation_editor::resourceSource;
```




<hr>
## Public Functions Documentation




### function captureAudio 

```C++
void gallery_relation_editor::captureAudio () 
```




<hr>



### function capturePhoto 

```C++
void gallery_relation_editor::capturePhoto () 
```




<hr>



### function captureVideo 

```C++
void gallery_relation_editor::captureVideo () 
```




<hr>

------------------------------
The documentation for this class was generated from the following file `src/qml/editorwidgets/relationeditors/gallery_relation_editor.qml`

