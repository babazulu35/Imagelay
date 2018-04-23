# Imagelay jQuery Plugin #
**Imagelay** is a simple jQuery plugin to view your image in overlay

## Version ##
0.1.0

## Usage ##
```
    $('.c-text-image__image').imagelay({
        mainClass: 'c-overlay',
        contentClass: 'c-overlay--content',
        closeIcon: 'c-overlay--close',
        animation: 'fadeIn',
        closeOnOutsideClick: true
    });
```
### Usage HTML Side ###
```
                    <div class="c-text-image__image" data-imagelay>
                        <img src="assets/images/image-content-left.jpg" />
                    </div>
```

## Vendors ##

jQuery [https://jquery.com/](https://jquery.com/)

## License ##
MIT License

