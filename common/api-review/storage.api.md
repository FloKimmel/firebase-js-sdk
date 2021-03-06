## API Report File for "@firebase/storage"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { FirebaseApp } from '@firebase/app';
import { FirebaseStorageError } from '@firebase/storage-types/exp';
import { ListOptions } from '@firebase/storage-types/exp';
import { ListResult } from '@firebase/storage-types/exp';
import { Metadata } from '@firebase/storage-types/exp';
import { StorageObserver } from '@firebase/storage-types/exp';
import { StorageReference } from '@firebase/storage-types/exp';
import { StorageService } from '@firebase/storage-types/exp';
import { TaskEvent } from '@firebase/storage-types/exp';
import { TaskState } from '@firebase/storage-types/exp';
import { UploadResult } from '@firebase/storage-types/exp';
import { UploadTask } from '@firebase/storage-types/exp';

// @public
export function deleteObject(ref: StorageReference): Promise<void>;

export { FirebaseStorageError }

// @public
export function getDownloadURL(ref: StorageReference): Promise<string>;

// @public
export function getMetadata(ref: StorageReference): Promise<Metadata>;

// @public
export function getStorage(app: FirebaseApp): StorageService;

// @public
export function list(ref: StorageReference, options?: ListOptions): Promise<ListResult>;

// @public
export function listAll(ref: StorageReference): Promise<ListResult>;

export { ListOptions }

export { ListResult }

export { Metadata }

// @public
export function ref(storage: StorageService, url?: string): StorageReference;

// @public
export function ref(storageOrRef: StorageService | StorageReference, path?: string): StorageReference;

export { StorageObserver }

export { StorageReference }

export { StorageService }

// @public
export type StringFormat = string;

// @public
export const StringFormat: {
    RAW: string;
    BASE64: string;
    BASE64URL: string;
    DATA_URL: string;
};

export { TaskEvent }

export { TaskState }

// @public
export function updateMetadata(ref: StorageReference, metadata: Partial<Metadata>): Promise<Metadata>;

// @public
export function uploadBytes(ref: StorageReference, data: Blob | Uint8Array | ArrayBuffer, metadata?: Metadata): Promise<UploadResult>;

// @public
export function uploadBytesResumable(ref: StorageReference, data: Blob | Uint8Array | ArrayBuffer, metadata?: Metadata): UploadTask;

export { UploadResult }

// @public
export function uploadString(ref: StorageReference, value: string, format?: string, metadata?: Metadata): Promise<UploadResult>;

export { UploadTask }


// (No @packageDocumentation comment for this package)

```
