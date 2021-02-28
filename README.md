# hello-world
import {Store} from './store';
import fetch from 'node-fetch';

export const NeweggCa: Store = {
  currency: '$',
  labels: {
    captcha: {
      container: 'body',
      text: ['are you a human?'],
    },
    inStock: {
      container: 'div#ProductBuy .btn-primary',
      text: ['add to cart'],
    },
    maxPrice: {
      container: 'div#app div.product-price > ul > li.price-current > strong',
      euroFormat: false,
    },
    outOfStock: [
      {
        container: '.product-inventory',
        text: [' out of stock.'],
      },
      {
        container: '.product-flag',
        text: ['out of stock '],
      },
    ],
  },
  links: [
    {
      brand: 'test:brand',
      model: 'test:model',
      series: 'test:series',
      url:
        'https://www.newegg.ca/p/N82E16824475043?Item=N82E16824475043&cm_sp=Homepage_MKPL-_-P3_24-475-043-_-12302020',
    },
    {
      brand: 'gigabyte',
      itemNumber: '14-932-399',
      model: 'eagle',
      series: '3060',
      url:
        'https://www.newegg.ca/gigabyte-geforce-rtx-3060-gv-n3060eagle-12gd/p/N82E16814932399',
    },
    {
      brand: 'gigabyte',
      itemNumber: '14-932-402',
      model: 'gaming oc',
      series: '3060',
      url:
        'https://www.newegg.ca/gigabyte-geforce-rtx-3060-gv-n3060gaming-oc-12gd/p/N82E16814932402',
    },
    {
      brand: 'msi',
      itemNumber: '14-137-630',
      model: 'gaming x',
      series: '3060',
      url:
        'https://www.newegg.ca/msi-geforce-rtx-3060-rtx-3060-gaming-x-12g/p/N82E16814137630',
    },
    {
      brand: 'asus',
      itemNumber: '14-126-493',
      model: 'dual',
      series: '3060',
      url:
        'https://www.newegg.ca/asus-geforce-rtx-3060-dual-rtx3060-12g/p/N82E16814126493',
    },
    {
      brand: 'asus',
      itemNumber: '14-126-491',
      model: 'tuf',
      series: '3060',
      url:
        'https://www.newegg.ca/asus-geforce-rtx-3060-tuf-rtx3060-o12g-gaming/p/N82E16814126491',
    },
    {
      brand: 'asus',
      itemNumber: '14-126-492',
      model: 'strix',
      series: '3060',
      url:
        'https://www.newegg.ca/asus-geforce-rtx-3060-rog-strix-rtx3060-o12g-gaming/p/N82E16814126492',
    },\

